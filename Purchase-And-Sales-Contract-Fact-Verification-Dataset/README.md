---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Purchase and Sales Contract Fact Verification Dataset
---

# Purchase and Sales Contract Fact Verification Dataset

This dataset provides factual claims about purchase and sales agreements, covering topics such as contracting parties, pricing, payment, delivery, warranties, and termination. Each example pairs agreement text with a claim, its verification outcome, supporting or refuting clause evidence, and an explanation, providing supervision for training and evaluating models that verify explicit contractual facts. It supports legal document analysis, contract review, and evidence tracing.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence | array | Relevant excerpts and clause locations that support or refute the verification result. |
| explanation | string | A concise explanation of how the cited agreement text determines the verification outcome. |
| is_supported | boolean | Whether the agreement explicitly supports the claim. |
| contract_text | string | The source text of the purchase or sales agreement used to verify the claim. |
| claim_statement | string | The factual statement to be checked against the agreement. |
| verification_status | string | The outcome of checking the claim against the agreement. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

