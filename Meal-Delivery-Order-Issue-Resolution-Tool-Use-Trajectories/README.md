---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Meal Delivery Order Issue Resolution Tool-Use Trajectories
---

# Meal Delivery Order Issue Resolution Tool-Use Trajectories

Focused on meal delivery after-sales issues such as missing items, incorrect deliveries, and food-related complaints, these records capture customer reports, order verification, issue categorization, and tool calls. They cover remedies such as replacements and refunds, along with execution outcomes, supporting training in gathering required information, selecting appropriate tools, and tracking resolution status. The trajectories can also help analyze exceptions and incomplete steps in order verification and issue resolution.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| tool_calls | array | Tool calls made during issue resolution, listed in execution order with their arguments and results. |
| issue_category | string | The primary reported meal delivery issue. |
| raw_trajectory | string | The original serialized conversation and tool-use trace, including the customer report and tool responses. |
| resolution_action | string | The final remedy selected or attempted for the reported issue. |
| resolution_status | string | The final known status of the selected remedy. |
| resolution_summary | string | A concise account of the outcome communicated or established by the tool-use trajectory. |
| order_verification_status | string | The outcome of checking whether the order and customer details were sufficient and valid for handling the issue. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

