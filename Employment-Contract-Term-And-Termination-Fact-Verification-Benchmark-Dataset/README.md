---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Employment Contract Term and Termination Fact Verification Benchmark Dataset
---

# Employment Contract Term and Termination Fact Verification Benchmark Dataset

This benchmark provides employment contract or clause text, claims to verify, structured contract facts, and claim assessments. It covers fixed terms, probation periods, renewals, notice periods, immediate termination, and post-employment obligations. Use it to evaluate whether models can identify contract duration, termination triggers, and notice requirements, then support their judgments with textual evidence.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | A claim or question whose facts must be checked against the employment contract text. |
| contract_text | string | The original text of an employment contract or related contract clause to be verified. |
| contract_facts | object | Structured facts extracted from the contract text, including term, probation, renewal, notice period, immediate termination, and post-employment obligations. |
| claim_assessment | object | The classification and assessment of the contract facts, termination conditions, and notice requirements relevant to the claim, with supporting evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

