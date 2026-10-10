---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Major Appliance Order Change and Cancellation Tool-Use Trajectory Dataset
---

# Major Appliance Order Change and Cancellation Tool-Use Trajectory Dataset

This dataset captures conversations and tool-use trajectories for major appliance after-sales order handling, including order status checks, eligibility reviews for changes or cancellations, and submission of the requested actions. It covers key details such as order information, fulfillment status, and business rules, along with tool responses that may indicate restrictions, rejection, or confirmation. It supports tool-use training, after-sales workflow simulation, and model evaluation, especially for handling failures and edge cases.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_trace | string | The original conversation and tool-use trace, stored as a JSON string. |
| order_snapshot | object | Order details, fulfillment status, and change or cancellation conditions extracted from the original trace. |
| decision_summary | object | A summary of the model's decision based on order status and business rules, along with the final handling outcome. |
| tool_call_sequence | array | An ordered record of order lookups, eligibility checks, action submissions, and tool responses. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

