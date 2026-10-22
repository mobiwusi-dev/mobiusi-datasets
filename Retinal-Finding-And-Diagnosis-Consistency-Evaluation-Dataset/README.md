---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Retinal Finding and Diagnosis Consistency Evaluation Dataset
---

# Retinal Finding and Diagnosis Consistency Evaluation Dataset

This evaluation dataset provides JSON records of structured clinical findings and diagnoses related to the retina, macula, and vitreous, with labels for consistency, conflict type, and explanation. It requires no image files as input and supports evaluation of a model's ability to detect contradictions within clinical records, as well as ophthalmic text quality control and model validation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| conflict_type | string | Categorizes the conflict between findings and diagnosis; use none when they are consistent. |
| is_consistent | boolean | Indicates whether the documented diagnosis is consistent with the structured clinical findings. |
| clinical_record | object | Structured clinical record containing retinal findings and diagnosis information. |
| conflict_explanation | string | Briefly explains the mismatch between findings and diagnosis, or why they are consistent. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

