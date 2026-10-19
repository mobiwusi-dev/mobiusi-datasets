---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Coastal Inundation Risk Counterfactual Question-Answering Dataset
---

# Coastal Inundation Risk Counterfactual Question-Answering Dataset

This dataset presents counterfactual questions about coastal locations, terrain, and baseline risk information, exploring how changes in relative sea level or other risk conditions may affect inundation depth, extent, frequency, and related hazards. By pairing baseline and counterfactual outcomes with explanations, it provides structured examples for sea-level rise risk analysis, causal comparison, and reasoning model training.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | Question asking how inundation depth, extent, frequency, or related risk would change under the counterfactual conditions. |
| reasoning | string | Causal explanation based on the location, terrain, baseline risk information, and counterfactual assumption. |
| baseline_outcome | string | Answer describing the inundation risk state in the baseline scenario. |
| coastal_location | string | Name of the coastal location or region addressed by the question. |
| risk_change_summary | string | Summary of the direction and magnitude of risk change in the counterfactual scenario compared with the baseline. |
| terrain_description | string | Description of local terrain features and their relevance to coastal inundation. |
| counterfactual_outcome | string | Answer describing the inundation risk state under the counterfactual assumption. |
| baseline_risk_information | string | Inundation depth, extent, frequency, or other risk information for the baseline scenario. |
| counterfactual_assumption | string | A change to sea level, terrain, or another risk-related condition relative to the baseline scenario. |
| baseline_relative_sea_level_m | number | Relative sea-level value specified for the baseline scenario, in meters. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

