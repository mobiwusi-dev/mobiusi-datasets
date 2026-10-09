---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Coastal Protection Measures Counterfactual Reasoning Dataset
---

# Coastal Protection Measures Counterfactual Reasoning Dataset

This dataset presents paired question-and-answer scenarios about coastal measures such as levees, tidal gates, and natural shoreline protection. It compares settings with or without protection, or with changes to measure status or design conditions, and examines potential inundation and residual risk in each case. Records cover baseline and counterfactual scenarios, risk changes, and explanations of protective effects, supporting counterfactual reasoning training, evaluation, and research for sea-level rise risk management. The text-based scenarios are not a substitute for site-specific engineering assessments or flood forecasts.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | Provides an integrated counterfactual reasoning answer to the question. |
| question | string | Asks for a counterfactual comparison or risk analysis across the two scenarios. |
| risk_change | string | Summarizes the direction and main differences in inundation risk between the two scenarios. |
| residual_risk | string | Explains the inundation risk that remains after a protection measure is implemented or its status changes. |
| baseline_scenario | string | Describes the coastal conditions, protection measures, and their status in the baseline scenario. |
| causal_explanation | string | Explains how the protection measure affects inundation risk and notes relevant conditions or limitations. |
| counterfactual_scenario | string | Describes changes to protection status, design conditions, or other relevant factors relative to the baseline scenario. |
| baseline_inundation_risk | string | Analyzes the level or characteristics of potential inundation risk in the baseline scenario. |
| counterfactual_inundation_risk | string | Analyzes the level or characteristics of potential inundation risk in the counterfactual scenario. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

