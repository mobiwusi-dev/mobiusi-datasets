---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cardiac Anesthesia Hemodynamic Constraint Evaluation Dataset
---

# Cardiac Anesthesia Hemodynamic Constraint Evaluation Dataset

This JSON dataset presents cardiac anesthesia patient and procedural contexts, individualized hemodynamic targets and boundaries, and candidate monitoring and management plans for evaluation. Annotations identify conflicts with case-specific constraints, omitted escalation triggers, and the overall assessment. It supports evaluation of models that validate patient-specific constraints, detect plan inconsistencies, and identify important omissions; it is intended for research and model safety testing, not as a substitute for clinical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| rationale | string | Concise evidence-based rationale supporting the evaluation result. |
| candidate_plan | object | Proposed monitoring and management plan supplied for evaluation. |
| patient_context | object | Patient and procedural information provided as an input source. |
| conflict_detected | boolean | Whether any part of the candidate plan conflicts with the patient-specific constraints. |
| conflict_findings | array | Specific conflicts identified between the candidate plan and the case constraints. |
| overall_assessment | string | Overall result of evaluating the plan against the case constraints. |
| hemodynamic_constraints | object | Patient-specific hemodynamic targets, boundaries, and escalation criteria supplied as an input source. |
| missing_escalation_triggers | array | Specified escalation triggers that are not adequately addressed in the candidate plan. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

