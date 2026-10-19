---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Conditional Contract Obligations Evidence Assessment Dataset
---

# Conditional Contract Obligations Evidence Assessment Dataset

This dataset focuses on obligation claims in procurement and sales agreements, including terms limited by prerequisites, exceptions, thresholds, or timing requirements. Each record links relevant contract text to an obligation claim, condition status, applicability decision, and supporting rationale, making it suitable for training and evaluating models that assess contractual evidence. It helps identify whether a condition is met, whether an obligation applies, and whether the text remains uncertain or contains a contrary term, reducing the risk of treating conditional obligations as unconditional.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reasoning | string | An explanation connecting the contract wording and condition status to the applicability classification. |
| contract_text | string | Relevant contract wording, including any conditions, exceptions, thresholds, or timing requirements. |
| condition_type | string | The primary condition affecting the obligation, such as a prerequisite, exception, threshold, timing requirement, or no identified condition. |
| condition_status | string | Indicates whether the relevant condition is satisfied, unsatisfied, unresolved, or inapplicable based on the available text. |
| evidence_excerpt | string | Relevant contract wording that supports, limits, leaves uncertain, or contradicts the claimed obligation. |
| obligation_claim | string | The procurement or sales obligation to assess against the contract text. |
| condition_summary | string | A concise explanation of the condition or limitation affecting the claimed obligation. |
| applicability_status | string | Indicates whether the contract text supports the obligation, leaves it unconfirmed, or contains a contrary term. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

