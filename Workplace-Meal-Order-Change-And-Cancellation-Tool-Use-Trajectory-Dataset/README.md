---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Workplace Meal Order Change and Cancellation Tool-Use Trajectory Dataset
---

# Workplace Meal Order Change and Cancellation Tool-Use Trajectory Dataset

This scenario-based dataset covers workplace catering requests to adjust meal quantities, modify orders, or cancel orders, along with the tool-use trajectories for checking order status, validating business rules, submitting changes, and confirming outcomes. It captures constraints imposed by deadlines and order states, with fields for the original interaction, request summary, order context, rule checks, tool actions, and final outcome. Use it to train and evaluate models that check conditions before taking action, invoke tools in the right sequence, and verify results.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_trace | string | The original conversation and tool-call trajectory, stored as a JSON-formatted string. |
| rule_checks | array | The business rules checked to determine whether the requested change is allowed. |
| tool_actions | array | The ordered tool calls used to inspect the order, check rules, submit a change, or confirm its result. |
| final_outcome | object | The final processing status and confirmation communicated or observed after the tool trajectory. |
| order_context | object | Order details and business state relevant to evaluating and processing the request. |
| request_summary | string | A concise summary of the customer's requested meal-order change or cancellation. |
| requested_change | object | The interpreted change requested by the customer. |
| trajectory_validated | boolean | Whether the trajectory checks order state and applicable rules before submission and verifies the result afterward. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

