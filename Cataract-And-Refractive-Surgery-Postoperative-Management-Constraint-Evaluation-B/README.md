---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cataract and Refractive Surgery Postoperative Management Constraint Evaluation Benchmark
---

# Cataract and Refractive Surgery Postoperative Management Constraint Evaluation Benchmark

This JSON benchmark records symptoms, examination findings, clinical course, and proposed management after cataract or refractive surgery, with annotations for case risk, required escalation level, and expected actions. It also captures workflow constraints, delay sensitivity, management alignment, and constraint violation codes, enabling evaluation of whether models detect conflicts between proposed recommendations and case risk or specified protocols. It supports domain evaluation of ophthalmic models and postoperative workflow verification, but does not replace clinical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| risk_level | string | The benchmark-assessed level of postoperative risk based on the supplied case facts. |
| procedure_type | string | The ophthalmic procedure performed, such as cataract surgery or refractive surgery. |
| clinical_course | string | Relevant events and changes in the patient's condition since surgery. |
| delay_sensitive | boolean | Whether the case requires avoiding delay in assessment or management. |
| required_action | string | A concise description of the benchmark-expected clinical follow-up or escalation action. |
| reported_symptoms | string | The patient's reported postoperative symptoms, including onset, severity, and change over time when available. |
| proposed_management | string | The follow-up, treatment, or escalation plan proposed for the case. |
| assessment_rationale | string | A concise explanation linking the case facts and constraints to the required escalation and management-alignment label. |
| examination_findings | string | Documented postoperative examination findings and relevant test results. |
| management_alignment | string | Whether the proposed management is consistent with the assessed risk and specified workflow constraints. |
| postoperative_interval | string | The time elapsed since surgery or the relevant timing of symptom onset and progression. |
| required_escalation_level | string | The minimum level of follow-up or assessment required by the case risk and specified workflow constraints. |
| constraint_violation_codes | array | Standardized codes identifying mismatches between the proposed management and required escalation or workflow constraints. |
| specified_workflow_constraints | string | Case-specific protocol or workflow requirements, including required review timing and restrictions on delaying assessment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

