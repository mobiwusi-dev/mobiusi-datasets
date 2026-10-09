---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Computer and Tablet Warranty and Repair Service Tool-Invocation Trajectory Dataset
---

# Computer and Tablet Warranty and Repair Service Tool-Invocation Trajectory Dataset

This dataset records tool-invocation trajectories for computer and tablet after-sales service, including warranty or service eligibility checks, repair option searches, service location lookups, and appointment booking. The trajectories show how a model gathers device or order details, calls lookup tools, handles returned results, and requests missing information when needed. They include raw interactions and structured task, device, eligibility, repair option, location, appointment, and outcome data for training and evaluating multi-step after-sales tool use.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_trace | object | Unprocessed source data containing the complete conversation and tool-call trace. |
| appointment | object | Records the booking status and appointment details. |
| device_info | object | Computer or tablet device and order details extracted from the conversation and tool calls. |
| final_status | string | Summary of the final outcome of the after-sales service task. |
| task_category | string | After-sales service task type inferred from the trajectory. |
| repair_options | array | Repair methods returned by tools, including available cost, timing, or coverage details. |
| service_locations | array | Repair service locations or provider details returned by tools. |
| conversation_steps | array | User, assistant, and tool interaction steps arranged in chronological order. |
| missing_information | array | Information the user still needs to provide before service can be checked or arranged. |
| service_eligibility | object | Records the device's warranty status, service eligibility, and related lookup results. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

