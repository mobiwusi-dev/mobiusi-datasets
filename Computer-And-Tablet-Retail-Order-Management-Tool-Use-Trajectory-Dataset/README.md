---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Computer and Tablet Retail Order Management Tool-Use Trajectory Dataset
---

# Computer and Tablet Retail Order Management Tool-Use Trajectory Dataset

This dataset covers computer and tablet retail scenarios involving order lookup, status tracking, and permitted order changes, capturing user requests, order context, and the model's tool-use process. Each trajectory records tool parameters and returned results, along with how the model selects follow-up actions or stops and explains limitations when information is missing or an operation is restricted. It is suitable for training and evaluating tool-use decisions, result follow-up, and constraint handling across the order lifecycle.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_trace | string | The complete, unstructured order tool-use trajectory, stored as JSON text. |
| tool_calls | array | The order tools called in sequence, including their arguments, returned results, and the model's subsequent decisions. |
| stop_reason | string | The reason processing could not continue, required additional information, or was restricted; may be omitted when not applicable. |
| final_status | string | The outcome of the order request when the trajectory ends. |
| request_type | string | The order-processing task type inferred from the user's request. |
| user_request | string | The user's original request to look up, track, or modify a computer or tablet order. |
| order_context | object | Order and product details extracted and confirmed from the trajectory; details that cannot be confirmed may be omitted. |
| assistant_response | string | The model's final message explaining the order status, completed actions, next steps, or execution limitations. |
| trajectory_summary | string | A brief summary of the order request, tool-use decisions, and processing outcome. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

