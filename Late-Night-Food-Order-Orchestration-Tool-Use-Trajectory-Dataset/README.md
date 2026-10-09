---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Late-Night Food Order Orchestration Tool-Use Trajectory Dataset
---

# Late-Night Food Order Orchestration Tool-Use Trajectory Dataset

This dataset captures end-to-end tool-use workflows for late-night food delivery, from interpreting a user's order request and searching for restaurants open at night and their menus to managing a cart and submitting an order. It records tool calls, returned observations, and subsequent actions, alongside organized information such as user intent, search results, cart state, submission outcome, and workflow status. Use it to train and evaluate models that invoke tools step by step and advance ordering tasks based on tool feedback.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_trace | string | The original trace text, preserving the user's food order request, tool calls, tool observations, and their sequence. |
| cart_state | string | Cart contents, item quantities, and order totals organized from the raw trace. |
| next_action | string | The next ordering step inferred or recorded from the final tool observation. |
| user_intent | string | The user's food requirements, preferences, and delivery instructions extracted from the raw trace. |
| order_submitted | boolean | Whether the order was successfully submitted, as determined from tool observations. |
| tool_call_count | integer | The total number of tool calls counted from the raw trace. |
| workflow_status | string | A summary of the current or final order orchestration status, such as completed, in progress, or failed. |
| menu_lookup_result | string | Restaurant menu items, available options, and prices organized from the raw trace. |
| order_submission_result | string | The order submission status, order details, or failure reason returned by the tools. |
| restaurant_search_result | string | Results for restaurants open at night and related filtering information, organized from the raw trace. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

