---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Air Express Network Shipment Planning Trajectory Dataset
---

# Air Express Network Shipment Planning Trajectory Dataset

This dataset captures multi-stage shipment planning trajectories across an air express network, including shipment requests, available hubs and flight connections, operating constraints, route choices, state changes, and agent decisions. It also provides planned routes, feasibility assessments, delivery-deadline margins, and shipment outcomes, supporting research on end-to-end freight planning under network and time constraints. It is suited to long-horizon agent training, planning strategy evaluation, and analysis of air express operations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| outcome | object | Observed or evaluated result following execution of the planned shipment trajectory. |
| planned_route | array | Ordered list of hubs or facilities selected for the shipment route. |
| network_snapshot | object | Snapshot of the available hubs and flight connections used for route planning. |
| plan_feasibility | string | Assessment of the proposed plan against operational constraints and the delivery deadline. |
| shipment_request | object | Original shipment details and service requirements provided as input to the planning process. |
| planning_trajectory | array | Ordered sequence of shipment states, planning stages, and agent decisions across the air express network. |
| operating_constraints | object | Operational limits and preferences that constrain the planning process. |
| delivery_deadline_margin_minutes | integer | Calculated number of minutes between the planned delivery time and the required deadline; negative values indicate a projected delay. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

