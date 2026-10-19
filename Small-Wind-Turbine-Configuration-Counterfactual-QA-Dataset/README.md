---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Small Wind Turbine Configuration Counterfactual QA Dataset
---

# Small Wind Turbine Configuration Counterfactual QA Dataset

This dataset focuses on configuration selection for small wind turbines, recording rotor diameter, rated power, and cut-in wind speed for baseline and alternative configurations. It compares expected performance under specified wind conditions and application constraints, such as site, load, installation, or budget requirements. Questions, direct answers, performance comparisons, and reasoning explanations support training and evaluation of configuration analysis and counterfactual reasoning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | The direct answer to the counterfactual question, stating the likely outcome or preferred configuration. |
| question | string | The user-facing question requesting a comparison or counterfactual inference about the turbine configurations. |
| reasoning | string | A concise explanation connecting configuration changes and operating context to the predicted performance differences and answer. |
| source_text | string | The original text containing the turbine scenario, configuration details, question, and any provided answer or explanation. |
| wind_speed_m_s | number | The wind speed or representative operating wind speed used to compare the configurations, in meters per second. |
| baseline_rated_power_w | number | The rated power of the baseline turbine configuration, in watts. |
| performance_comparison | string | A comparison of expected performance differences between the baseline and alternative configurations under the stated wind conditions and application constraints. |
| application_constraints | string | Site, load, installation, budget, safety, or other application constraints relevant to selecting a turbine configuration. |
| baseline_rotor_diameter_m | number | The rotor diameter of the baseline turbine configuration, in meters. |
| counterfactual_rated_power_w | number | The rated power of the alternative turbine configuration being evaluated, in watts. |
| baseline_cut_in_wind_speed_m_s | number | The minimum wind speed at which the baseline turbine begins generating power, in meters per second. |
| counterfactual_rotor_diameter_m | number | The rotor diameter of the alternative turbine configuration being evaluated, in meters. |
| counterfactual_cut_in_wind_speed_m_s | number | The minimum wind speed at which the alternative turbine begins generating power, in meters per second. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

