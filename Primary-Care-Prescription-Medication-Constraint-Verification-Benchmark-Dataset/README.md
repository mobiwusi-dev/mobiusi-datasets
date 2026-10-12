---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Primary Care Prescription Medication Constraint Verification Benchmark Dataset
---

# Primary Care Prescription Medication Constraint Verification Benchmark Dataset

This structured JSON benchmark records patient information, proposed medications, and prescription regimens, with labels indicating whether relevant medication constraints are violated. It covers review factors such as allergies, concomitant medications, dosage, and renal function, supporting evaluation of constraint reasoning, violation detection, and result explanation in primary care prescription review.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| violations | array | Constraints violated by the proposed prescription, with supporting rationale and evidence. |
| review_summary | string | A concise explanation of the overall prescription verification result. |
| patient_context | object | Structured patient information used as input for prescription constraint verification. |
| proposed_prescription | object | The medication and regimen assessed for potential constraint violations. |
| is_prescription_acceptable | boolean | Indicates whether the proposed prescription complies with the medication constraints being assessed. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

