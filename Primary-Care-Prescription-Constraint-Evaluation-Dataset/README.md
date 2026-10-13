---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Primary Care Prescription Constraint Evaluation Dataset
---

# Primary Care Prescription Constraint Evaluation Dataset

This evaluation dataset uses structured JSON to capture primary care patients' medication backgrounds, proposed prescriptions, and related safety constraints, including allergies, prior medication use, patient-specific factors, and dosage limits. Each case is labeled to indicate whether the proposed prescription violates a constraint; violations include specific reasons and supporting evidence. The data supports systematic evaluation of prescription safety reasoning, clinical decision support models, and medication safety workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | Structured JSON containing the patient's medication background, proposed prescription, and relevant constraints. |
| violation_reasons | array | Lists each violated constraint, its specific reason, and supporting evidence; an empty array indicates no constraint violation. |
| has_constraint_violation | boolean | Indicates whether the proposed prescription violates any stated prescription safety constraint. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

