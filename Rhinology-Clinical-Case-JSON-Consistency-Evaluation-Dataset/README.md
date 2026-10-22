---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Rhinology Clinical Case JSON Consistency Evaluation Dataset
---

# Rhinology Clinical Case JSON Consistency Evaluation Dataset

This dataset contains structured rhinology case information, including fields such as symptoms, nasal endoscopy and imaging findings, diagnoses, and affected side. Each case is accompanied by a reference consistency judgment and, where relevant, a contradiction category and explanation. It supports evaluation of models that detect conflicts between clinical fields, as well as research on structured rhinology data processing and consistency checking.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| clinical_case | object | Original structured rhinology case information used as the input source. |
| contradiction_type | string | Reference category of the conflict between case fields, or none when the case is consistent. |
| expected_consistency | boolean | Reference judgment indicating whether the clinical case fields are mutually consistent. |
| contradiction_explanation | string | Brief explanation identifying the conflicting fields and the nature of the inconsistency, if present. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

