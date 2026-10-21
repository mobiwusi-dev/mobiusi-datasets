---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Service Dependency Health State Transition Dataset
---

# Service Dependency Health State Transition Dataset

Each record captures a monitored service's health at a specific observation time, the states of its infrastructure dependencies, and recent related events, alongside the predicted service health and transition direction over a defined horizon. Records also include the affected dependency chain and a risk score from 0 to 1, supporting analysis of how dependency changes relate to service health. The data is suitable for service state prediction, failure early warning, and operational decision support.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| risk_score | number | Estimated probability of service degradation or failure within the prediction horizon, on a scale from 0 to 1. |
| service_name | string | Name of the monitored service for which the next health state is predicted. |
| recent_events | array | Events affecting the service or its dependencies before or during the observation. |
| observation_time | string | Timestamp when the current service and dependency states were observed. |
| dependency_states | array | Observed state and criticality of each infrastructure dependency used by the monitored service. |
| predicted_transition | string | Predicted direction of change from the current service health state to the next state. |
| predicted_next_health | string | Predicted health state of the monitored service at the end of the prediction horizon. |
| current_service_health | string | Observed health state of the monitored service at the observation time. |
| affected_dependency_chain | array | Ordered names of dependencies predicted to contribute to the service's next health state. |
| prediction_horizon_minutes | integer | Number of minutes from the observation time to the predicted next health state. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

