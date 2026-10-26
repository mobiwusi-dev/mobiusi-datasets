---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Urban Delivery Disruption-Driven Short-Horizon Replanning Trajectory Dataset
---

# Urban Delivery Disruption-Driven Short-Horizon Replanning Trajectory Dataset

This dataset contains agent state-decision trajectories following disruptions in urban delivery, including temporary road closures, impassable street segments, and blocked delivery entrances. Records cover disruption observations, the current delivery state, affected tasks, and plans before and after replanning. The data supports short-horizon task replanning and evaluation of whether revised delivery plans are executable under updated conditions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| revised_plan | array | New ordered sequence of delivery actions produced in response to the updated state. |
| affected_tasks | array | Task references whose route, order, or execution status changed because of the disruption. |
| plan_executable | boolean | Indicates whether the revised plan can be carried out under the observed state and constraints. |
| decision_summary | string | Concise explanation of how the agent adapted the plan to the disruption and current delivery state. |
| replanning_metrics | object | Computed summary measures describing the revised plan. |
| pre_disruption_plan | array | Ordered plan active immediately before the disruption was processed. |
| current_delivery_state | object | Raw vehicle and task state available to the agent when replanning begins. |
| disruption_observation | object | Raw report describing the temporary road closure, blocked street segment, or obstructed delivery entrance. |
| replanning_trigger_classification | string | Normalized category of the disruption that triggered replanning. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

