---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Storage Device Wear and Health State Prediction Dataset
---

# Storage Device Wear and Health State Prediction Dataset

This simulated time-series dataset represents HDD and SSD workloads, device telemetry, and lifecycle changes, with observations such as read and write volume, IOPS, temperature, media wear, and cumulative power-on hours. It also includes targets and estimates such as current and future health status, degradation risk, remaining useful life, and predicted wear, making it suitable for studying how storage hardware health changes over time. Use it to train and evaluate models for health prediction, wear trend analysis, failure warning, and remaining-life estimation in storage operations and predictive maintenance research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| read_iops | number | Number of read operations per second during the observation interval. |
| write_iops | number | Number of write operations per second during the observation interval. |
| device_type | string | Type of storage device, such as HDD or SSD. |
| sample_time | string | Timestamp associated with this device observation. |
| power_on_hours | number | Total time the device has been powered on up to the observation time, in hours. |
| media_wear_percent | number | Media wear level recorded by device telemetry, expressed as a percentage. |
| temperature_celsius | number | Device temperature recorded by telemetry, in degrees Celsius. |
| workload_read_bytes | number | Amount of data read from the device during the observation interval, in bytes. |
| future_health_status | string | Health status at a future target time, derived from current and historical observations or provided as a prediction target. |
| workload_write_bytes | number | Amount of data written to the device during the observation interval, in bytes. |
| current_health_status | string | Device health status at the observation time, such as healthy, warning, or failed. |
| predicted_wear_percent | number | Predicted media wear level at the end of the prediction horizon, expressed as a percentage. |
| health_degradation_risk | number | Risk score for device health degradation within the prediction horizon, ranging from 0 to 1. |
| estimated_remaining_life_hours | number | Estimated remaining usable device life based on its lifecycle state, in hours. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

