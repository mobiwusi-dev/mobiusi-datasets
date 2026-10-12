---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Opioid Use Disorder Medication Initiation Constraint Verification Benchmark
---

# Opioid Use Disorder Medication Initiation Constraint Verification Benchmark

This benchmark uses structured JSON to represent patient cases involving opioid use disorder, applicable clinical constraints, and candidate medication initiation plans. Labels indicate whether a plan violates a constraint, the severity and codes of any violations, and the rationale for the assessment. It supports domain evaluation of models that identify relevant patient and plan details, check applicable conditions, and explain constraint judgments in addiction medicine. Dataset size and case provenance are not specified in the provided information; consult the dataset documentation for details.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | Original structured JSON input describing the patient, applicable clinical constraints, and candidate medication initiation plan. |
| violation_severity | string | Overall severity of the identified violation, or none when no violation is present. |
| assessment_rationale | string | Concise explanation of the constraint assessment, including relevant patient facts and plan details. |
| constraint_violation | boolean | Whether the candidate medication initiation plan violates at least one applicable clinical constraint or safety condition. |
| violated_constraint_codes | array | Codes of the supplied clinical constraints violated by the candidate plan. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

