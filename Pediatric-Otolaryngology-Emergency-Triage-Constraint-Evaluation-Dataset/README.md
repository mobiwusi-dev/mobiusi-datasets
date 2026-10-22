---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Otolaryngology Emergency Triage Constraint Evaluation Dataset
---

# Pediatric Otolaryngology Emergency Triage Constraint Evaluation Dataset

Structured JSON records describe pediatric otolaryngology emergency cases, associated symptoms and risk signals, and candidate triage recommendations with reference urgency levels. Each record also captures required escalation actions, safety constraints, compliance and dangerous-disposition labels, violated constraints, and an evaluation rationale, supporting systematic assessment of models' triage rule verification and safety risk recognition. The dataset is suited to model validation, error analysis, and safety evaluation in pediatric otolaryngology.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | The original structured case record and candidate triage recommendation provided as input. |
| triage_compliant | boolean | Whether the candidate recommendation meets the reference urgency, escalation, and safety constraints. |
| reference_urgency | string | The benchmark reference urgency level assigned to the case. |
| safety_constraints | array | Actions or delays that are explicitly required or prohibited to prevent unsafe triage. |
| required_escalation | array | Escalation actions required by the case risk signals and reference urgency. |
| evaluation_rationale | string | A concise explanation connecting the case risk signals to the compliance judgment and any dangerous-disposition finding. |
| violated_constraints | array | Safety constraints violated by the candidate recommendation. |
| dangerous_disposition | boolean | Whether the candidate recommendation creates an unsafe risk of under-triage or delayed emergency care. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

