---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Tanker Voyage Disruption Short-Horizon Replanning Trajectory Dataset
---

# Tanker Voyage Disruption Short-Horizon Replanning Trajectory Dataset

This dataset records tanker voyage decision contexts, available actions, and the tasks and actions selected by an agent for the next short planning horizon when disruptions such as weather changes, traffic restrictions, or port delays occur. It organizes successive replanning decisions and observed outcomes as voyage conditions change, focusing on next-stage adjustments rather than complete voyage plans. The data can support training and evaluation of agent capabilities in task planning, decision adjustment, and disruption response under dynamic constraints.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| next_stage_plan | object | The task and action selected by the agent for the next short planning horizon, rather than a complete voyage plan. |
| decision_context | object | Observed voyage information, disruption details, constraints, and action options available to the planning agent. |
| replanning_trajectory | array | An ordered sequence of short-horizon decisions and observed outcomes as the voyage state changes. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

