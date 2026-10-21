---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Endpoint Management Agent Health Anomaly Evaluation Dataset
---

# Endpoint Management Agent Health Anomaly Evaluation Dataset

Covers multivariate time series for endpoint management and security agents, including heartbeat intervals, policy synchronization, signature or rule updates, scan activity, service status, and telemetry reporting. Records are labeled for events such as agent unavailability, stale state, and functional anomalies. The data supports evaluation of agent health monitoring, anomaly detection, and classification models, as well as endpoint health analysis, troubleshooting, and monitoring solution validation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| state_stale | boolean | Indicates whether policy, signatures, rules, or telemetry are older than expected. |
| anomaly_type | string | The primary classified anomaly, such as an unreachable agent, stale state, service failure, or scan malfunction. |
| anomaly_score | number | The computed anomaly severity score for the agent health record. |
| health_status | string | The overall derived health classification for the agent, such as healthy, degraded, or unhealthy. |
| telemetry_record | object | The original timestamped endpoint agent telemetry record containing health and activity measurements. |
| agent_unreachable | boolean | Indicates whether the heartbeat pattern suggests that the agent is disconnected or unavailable. |
| functional_anomaly | boolean | Indicates whether agent service or scan behavior shows a functional abnormality. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

