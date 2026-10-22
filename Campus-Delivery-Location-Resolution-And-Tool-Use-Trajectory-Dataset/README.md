---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Campus Delivery Location Resolution and Tool-Use Trajectory Dataset
---

# Campus Delivery Location Resolution and Tool-Use Trajectory Dataset

This dataset covers conversations in which users describe delivery locations through building names, dormitories, entrances, or campus landmarks, along with location lookup and delivery address tool-call traces. It focuses on resolving campus locations from conversational context and generating structured tool arguments for campus meal delivery. The sample count and campus coverage are not specified.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_trajectory | string | The original conversation and associated location lookup and delivery address tool-call trace, preserved as provided. |
| delivery_intent | string | The delivery-related intent inferred from the original trajectory. |
| resolution_status | string | The outcome of resolving the campus delivery location, such as resolved, ambiguous, or not found. |
| resolved_location | object | The structured campus location resolved from the user's description and conversational context. |
| tool_call_sequence | array | The ordered tool calls used to look up or submit the resolved campus delivery address. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

