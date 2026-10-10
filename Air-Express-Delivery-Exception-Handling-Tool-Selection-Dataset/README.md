---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Air Express Delivery Exception Handling Tool Selection Dataset
---

# Air Express Delivery Exception Handling Tool Selection Dataset

This dataset covers air express delivery exceptions such as address issues, unsuccessful deliveries, held shipments, and transit delays. Each example presents the handling process through the original exception record, an ordered tool-use trajectory, the final disposition, and a response for the customer or operator. The examples show how to select tools for event lookup, address verification, redelivery, or follow-up, supporting supervised fine-tuning for tool selection and exception handling. Typical applications include air express support automation, logistics operations assistance, and tool-use evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| tool_calls | array | The tools selected and called to handle the delivery exception, recorded in execution order with their parameters, results, and selection rationale. |
| source_record | string | The original exception scenario and related input information stored as JSON text. It may include shipment status, exception details, address information, and available tools. |
| final_disposition | string | The final handling plan formed after tool use, such as verifying an address, arranging redelivery, or initiating follow-up. |
| assistant_response | string | The final message explaining the exception outcome and next steps to the customer or operations staff. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

