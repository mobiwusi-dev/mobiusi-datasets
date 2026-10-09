---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Refrigerated Transport Dispatch Orchestration Tool-Use Trajectory Dataset
---

# Refrigerated Transport Dispatch Orchestration Tool-Use Trajectory Dataset

This dataset captures multi-tool agent interactions for dispatching vehicles to cold-chain orders. It covers vehicle and refrigeration capabilities, cargo temperature-control requirements, driver availability, routes, and delivery windows, documenting the process from information retrieval to dispatch-plan generation. Its fields include raw tool traces, order requirements, ordered tool calls, dispatch plans, and final outcome summaries, supporting the training and evaluation of agents that coordinate transport operations tools for refrigerated truck dispatch.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| tool_calls | array | Tool calls parsed from the raw trace, including their inputs, outputs, and execution status, ordered by invocation. |
| dispatch_plan | object | The dispatch plan produced after considering vehicle refrigeration capabilities, driver availability, routes, and delivery windows. |
| raw_tool_trace | string | The complete raw interaction trace between the agent and transport operations tools, recorded as JSON text. |
| dispatch_result | string | The agent's final dispatch decision, summary of constraint checks, or reason dispatch could not be arranged. |
| order_requirements | object | Cold-chain order, cargo temperature-control, and delivery requirements extracted from the raw trace. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

