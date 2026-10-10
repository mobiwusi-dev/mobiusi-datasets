---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Industrial HVAC Equipment Specification Question-Answer Verification Dataset
---

# Industrial HVAC Equipment Specification Question-Answer Verification Dataset

This dataset focuses on industrial air-conditioning and HVAC equipment specifications, including model numbers, cooling capacity, airflow, electrical parameters, and dimensions. Records provide questions, candidate answers, and structured reference information that may include reference answers, equipment specifications, numerical tolerances, and supporting sources, enabling automated answer checks with documented reasoning. It supports specification question-answer evaluation, model quality validation, and the improvement of industrial-domain QA systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | A question to be answered about an industrial HVAC equipment model or specification. |
| is_correct | boolean | Indicates whether the candidate answer is correct based on the reference data and applicable tolerances. |
| reference_data | object | Reference answers, equipment specifications, numerical tolerances, and supporting sources used to determine answer correctness. |
| candidate_answer | string | A model response to be evaluated against the reference answer and specification data. |
| evaluation_basis | string | A summary of how the candidate answer matches the reference answer or equipment specifications, including the reason for the decision. |
| evaluation_status | string | The evaluation outcome, which may be correct, incorrect, partially correct, or indeterminate. |
| discrepancy_summary | string | Specification items and numerical differences that do not match the reference data; may be empty when there are no discrepancies. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

