---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Virtual Care Safety Escalation Constraint Evaluation Dataset
---

# Virtual Care Safety Escalation Constraint Evaluation Dataset

This evaluation dataset presents patient symptom reports, risk conditions, virtual care contexts, and escalation rules in structured JSON, with labels indicating whether emergency referral, in-person assessment, or other specified actions are required. It supports checking the consistency of escalation labels against applicable rules and evaluating model constraint reasoning and safe escalation decisions. Intended for virtual care model validation, workflow quality assurance, and safety evaluation, it is not a substitute for clinical decision-making.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_case | object | The source patient report, risk conditions, virtual care context, and escalation rules for the case. |
| decision_rationale | string | A concise explanation connecting the source information and applicable rules to the derived escalation labels. |
| applicable_rule_indices | array | One-based positions of the supplied escalation rules that support the derived labels. |
| other_escalation_actions | array | Other required escalation measures specified by the case rules, excluding emergency referral and in-person assessment. |
| emergency_referral_required | boolean | Whether the case and supplied escalation rules require an emergency referral. |
| constraint_validation_status | string | Indicates whether the derived escalation labels are consistent with the supplied rules or the case is indeterminate. |
| in_person_assessment_required | boolean | Whether the case and supplied escalation rules require an in-person assessment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

