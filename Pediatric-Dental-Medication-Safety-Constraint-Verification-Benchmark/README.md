---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Dental Medication Safety Constraint Verification Benchmark
---

# Pediatric Dental Medication Safety Constraint Verification Benchmark

This JSON benchmark records patient age, weight, allergy history, current medications, and proposed prescriptions in pediatric dental scenarios, with labels indicating whether medication safety constraints are violated. Each record includes an assessment status, specific violated constraints, and a rationale, supporting evaluation of a model's ability to identify dosing issues, contraindications, and other medication risks. It is intended for model evaluation and research in pediatric dental medication safety, not as a substitute for professional clinical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| allergy_history | string | Known medication allergies and relevant allergy details; use an explicit value such as none known when appropriate. |
| violation_status | string | Overall determination of whether the proposed prescription violates medication constraints or whether the available information is insufficient. |
| patient_age_years | number | Patient age in years, including a fractional value when needed. |
| patient_weight_kg | number | Patient weight in kilograms for evaluating weight-based medication dosing. |
| current_medications | array | Medications the patient is currently taking, including relevant dose and route information. |
| assessment_rationale | string | Concise overall reasoning connecting the patient context and proposed prescription to the safety determination. |
| constraints_violated | boolean | Whether at least one medication safety constraint is determined to be violated; false when no violation is identified. |
| violated_constraints | array | Specific violated constraints identified in the assessment, with a category and explanation for each. |
| proposed_prescription | object | Medication prescription proposed for the pediatric dental scenario. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

