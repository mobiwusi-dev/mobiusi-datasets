---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: ITSM Service Level Agreement Escalation Constraint Verification Dataset
---

# ITSM Service Level Agreement Escalation Constraint Verification Dataset

This benchmark dataset represents IT service incidents in JSON, including priority, service level agreement (SLA), timestamps, work calendars, response and resolution targets, and proposed escalation actions. Each case applies explicit business-time calculations and escalation rules to determine whether an action meets timing and escalation constraints, with verifiable reward signals for evaluating incident-handling logic, constraint verification, and reinforcement learning with verifiable rewards.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| incident | object | IT service incident details used to evaluate SLA timing and escalation status. |
| sla_policy | object | Applicable response, resolution, and escalation thresholds for the incident. |
| work_calendar | object | Calendar settings used to calculate business time and SLA deadlines. |
| proposed_action | object | The action checked against SLA timing and escalation constraints. |
| violation_codes | array | Machine-checkable codes identifying SLA or escalation constraints violated by the proposed action. |
| action_compliant | boolean | Whether the proposed action meets the applicable timing and escalation constraints. |
| escalation_required | boolean | Whether SLA rules require escalation at the proposed action time. |
| verification_reward | number | Verifiable reward value derived from whether the proposed action satisfies the SLA constraints. |
| response_deadline_at | string | Calculated response deadline based on the work calendar and response target. |
| resolution_deadline_at | string | Calculated resolution deadline based on the work calendar and resolution target. |
| business_elapsed_minutes | number | Business minutes from incident creation to the proposed action timestamp. |
| required_escalation_level | integer | Escalation level required by the applicable threshold at the proposed action time. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

