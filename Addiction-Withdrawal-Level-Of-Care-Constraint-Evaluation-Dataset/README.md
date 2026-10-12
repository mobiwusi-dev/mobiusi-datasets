---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Addiction Withdrawal Level-of-Care Constraint Evaluation Dataset
---

# Addiction Withdrawal Level-of-Care Constraint Evaluation Dataset

This evaluation dataset presents structured cases involving addiction withdrawal, including risk conditions, care-resource constraints, and a proposed level-of-care recommendation to validate. Each case includes a reference judgment indicating whether the recommendation satisfies the stated constraints and identifying potential conflicts, supporting evaluation of constraint reasoning and recommendation validation in addiction psychiatry. The dataset is intended for research and model evaluation, not as a substitute for professional clinical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | Structured case information and the proposed level-of-care recommendation to be evaluated. |
| evaluation_summary | string | Concise summary of the benchmark case and its constraint-validation outcome. |
| reference_annotation | object | Benchmark judgment on whether the proposed recommendation satisfies the case constraints, including the rationale. |
| constraint_validation | object | Normalized validation result derived from the case input and reference annotation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

