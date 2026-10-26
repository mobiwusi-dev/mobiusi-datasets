---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Service Health State Transition Dataset
---

# Service Health State Transition Dataset

This dataset records infrastructure service metrics snapshots, logs, distributed traces, and relevant deployment or configuration events from observation windows, alongside the current state, subsequent state, transition timestamp, and time to transition. It covers changes among states such as healthy, degraded, failed, and recovered, supporting analysis of how observability signals relate to service health over time. It is suitable for next-state prediction, service health assessment, and training or evaluating infrastructure monitoring models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| next_state | string | The subsequent service health state used as the target for transition prediction or evaluation. |
| logs_window | array | Raw service log entries collected during the observation window. |
| current_state | string | The service health state at the end of the observation window, derived from available observability signals. |
| traces_window | array | Raw distributed trace data collected during the observation window. |
| metrics_snapshot | object | Raw service metrics from the observation window, such as latency, request rate, error rate, and resource utilization. |
| deployment_events | array | Deployment or configuration change events relevant to the service and observation window. |
| transition_timestamp | string | The timestamp when the transition to the next service state occurs. |
| time_to_transition_seconds | number | Elapsed time from the end of the observation window until the next state transition. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

