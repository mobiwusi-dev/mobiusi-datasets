---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Conference Event Scheduling and Venue Turnover Constraint Verification Dataset
---

# Conference Event Scheduling and Venue Turnover Constraint Verification Dataset

This dataset covers multi-day conference agendas, event dependencies, setup and teardown timing, and venue configuration changes, with candidate schedules and step-by-step constraint-check annotations. Prompt and text-plan examples support the identification of timing conflicts, dependency-order errors, insufficient turnover buffers, and inconsistencies between verification steps. It is designed for training and evaluating process verifiers, as well as reviewing schedules and improving operations at conference hotels and event venues.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| input_prompt | string | The original prompt describing conference dates, event dependencies, time limits, and venue transition requirements. |
| overall_result | string | A summary conclusion on the overall feasibility of the candidate schedule. |
| constraint_checks | array | Verification steps covering timing conflicts, dependency order, venue turnover buffers, and consistency between steps. |
| normalized_events | array | Events, times, venues, and transition details parsed from the prompt and candidate schedule. |
| violation_summary | string | A summary of issues such as timing conflicts, dependency-order errors, or insufficient turnover buffers; states when no violations are found. |
| candidate_schedule | string | The proposed multi-day conference agenda and venue setup transition plan to be verified. |
| step_consistency_result | string | Indicates whether the step-by-step checks contain inconsistencies in their conclusions, evidence, or order. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

