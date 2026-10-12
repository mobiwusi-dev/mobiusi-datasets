---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Clinical Psychology Risk Triage Constraint Verification Dataset
---

# Clinical Psychology Risk Triage Constraint Verification Dataset

This JSON dataset presents case-specific risk factors, protective factors, and recent changes alongside applicable triage and escalation rules, candidate dispositions, and verification outcomes. It supports domain evaluation and quality analysis of models that identify omitted conditions, rule violations, or inconsistencies between a proposed disposition and the case information. It is intended for model evaluation and does not replace professional clinical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| triage_rules | array | Source rules defining triage thresholds, escalation requirements, or other required actions. |
| risk_alignment | boolean | Indicates whether the candidate disposition is consistent with the documented risk and protective information. |
| required_action | string | The action required by the applicable rules and case information, if any. |
| review_rationale | string | A concise explanation connecting the case information and applicable constraints to the verification outcome. |
| case_risk_profile | object | Source information describing case-specific risk factors, protective factors, and recent changes. |
| overall_assessment | string | Derived outcome indicating whether the candidate disposition satisfies the applicable constraints. |
| constraint_findings | array | Derived findings identifying omitted conditions, constraint violations, or inconsistencies. |
| candidate_disposition | object | The proposed clinical risk disposition to be checked against the case information and applicable rules. |
| constraint_compliance | boolean | Indicates whether the candidate disposition complies with all applicable explicit triage and escalation constraints. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

