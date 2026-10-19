---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Network Segmentation Change Safe Rollback and Replanning Trajectory Dataset
---

# Network Segmentation Change Safe Rollback and Replanning Trajectory Dataset

This dataset captures agent decision trajectories after network segmentation policy changes encounter anomalies, including incident context, risk assessment, rollback or partial-reversal choices, recovery actions, and network-state verification. The trajectories also record residual risks and replacement change plans, showing the decision chain from failure detection through safe replanning. They support training and evaluation of network segmentation agents for incident recovery, self-correction, and change planning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| incident_input | object | Change context, observed anomalies, and post-failure network state from the original incident record. |
| risk_assessment | object | The agent's identification of risks and assessment of their impact based on the original incident information. |
| recovery_actions | array | Rollback or partial-reversal actions planned by the agent, along with their expected effects. |
| replacement_plan | object | A safer alternative segmentation policy plan proposed after recovery and state verification. |
| recovery_decision | object | The agent's choice to roll back, partially reverse, or defer action in response to the failed change. |
| trajectory_summary | string | A summary of the decision chain covering anomaly detection, recovery selection, state verification, and replanning. |
| verification_result | object | Network state confirmation, check results, and residual risks recorded after recovery actions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

