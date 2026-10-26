---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: IT Configuration Drift Anomaly Detection Benchmark
---

# IT Configuration Drift Anomaly Detection Benchmark

This benchmark contains periodic multivariate observations of IT configuration items relative to their baselines, covering details such as versions, policy compliance, and change status. It labels whether anomalous drift occurred, along with its category, severity, and time interval. The data supports evaluation of continuous configuration monitoring, baseline deviation detection, and anomaly localization, and is suited to baseline audits, change oversight, and anomaly detection validation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| drift_annotation | object | Benchmark labels indicating whether anomalous drift occurred and, if applicable, its category, severity, and time interval. |
| baseline_comparison | object | Comparison features computed from the observed configuration state and its baseline. |
| configuration_observation | object | A raw snapshot of a configuration item, including its observed state relative to the baseline. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

