---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: mmWave RAN Coverage Feasibility Reasoning Dataset
---

# mmWave RAN Coverage Feasibility Reasoning Dataset

This dataset presents mmWave RAN coverage scenarios as question-and-answer examples, with inputs such as carrier frequency, transmit power, antenna gains, propagation loss, obstruction, coverage distance, and coverage targets. It includes feasibility judgments, limiting factors, and expert reasoning grounded in link-budget and propagation analysis. Use it to train or evaluate models that quantify coverage requirements, identify constraints, and provide evidence-based conclusions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| expert_answer | string | A concise final answer to the original coverage feasibility question. |
| frequency_ghz | number | The operating carrier frequency, measured in gigahertz. |
| link_margin_db | number | The predicted received power minus receiver sensitivity, measured in dB. |
| expert_reasoning | string | A step-by-step explanation linking the link budget, propagation conditions, obstruction, and coverage target to the feasibility judgment. |
| limiting_factors | array | The key factors that constrain or prevent the required coverage. |
| coverage_feasible | boolean | Whether the stated coverage requirement is feasible under the supplied assumptions. |
| scenario_question | string | The original question describing the mmWave RAN coverage scenario to assess. |
| transmit_eirp_dbm | number | The transmitter's effective isotropic radiated power, measured in dBm. |
| coverage_target_pct | number | The required percentage of locations or users that must receive coverage. |
| obstruction_loss_db | number | The additional loss attributed to blockage or other obstructions, measured in dB. |
| rx_antenna_gain_dbi | number | The receive antenna gain, measured in dBi. |
| tx_antenna_gain_dbi | number | The transmit antenna gain, measured in dBi, when supplied separately from EIRP. |
| estimated_path_loss_db | number | The estimated propagation loss between the transmitter and receiver, measured in dB. |
| propagation_conditions | string | The stated propagation context, such as line of sight, non-line of sight, indoor, or outdoor conditions. |
| receiver_sensitivity_dbm | number | The minimum received power required by the receiver, measured in dBm. |
| predicted_received_power_dbm | number | The received power estimated from the supplied link-budget inputs, measured in dBm. |
| required_coverage_distance_m | number | The distance the deployment is required to cover, measured in meters. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

