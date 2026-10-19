---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Counterfactual Reasoning QA Dataset for Ozone Precursor Emission Controls
---

# Counterfactual Reasoning QA Dataset for Ozone Precursor Emission Controls

This question-answer dataset presents hypothetical controls on nitrogen oxides (NOx) or volatile organic compounds (VOCs), with questions and reference answers about their potential effects on near-surface ozone. It covers expected ozone responses, relevant atmospheric chemical mechanisms, environmental conditions, and important uncertainties. The examples support qualitative causal analysis of emissions interventions and can be used for reasoning-focused supervised fine-tuning and evaluation in ground-level ozone research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | Question about how the intervention may affect near-surface ozone and which factors determine the response. |
| ozone_response | string | Expected direction and qualitative nature of the ozone response under the stated control scenario. |
| causal_reasoning | string | Concise explanation connecting the emissions intervention, chemical and environmental factors, and expected ozone outcome. |
| control_scenario | string | Description of the hypothetical nitrogen oxide or volatile organic compound emissions control intervention. |
| reference_answer | string | Answer explaining the expected ozone response and the relevant mechanisms and conditions. |
| chemical_mechanisms | string | Relevant atmospheric chemistry, including ozone production sensitivity or titration effects, that helps explain the response. |
| intervention_target | string | Precursor or precursors targeted by the emissions control, such as nitrogen oxides, volatile organic compounds, or both. |
| environmental_conditions | string | Environmental and meteorological factors that influence the expected ozone response, such as sunlight, temperature, or mixing conditions. |
| uncertainty_and_dependencies | string | Assumptions, uncertainties, or additional conditions that could change the expected ozone response. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

