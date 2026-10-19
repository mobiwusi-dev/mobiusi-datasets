---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Sediment Internal Nutrient Loading Counterfactual QA Dataset
---

# Sediment Internal Nutrient Loading Counterfactual QA Dataset

This dataset presents structured question-answer examples about waterbodies where sediment nutrient release, legacy nutrient accumulation, and changes in external loads interact. It covers causal factors such as external inputs, internal loading, legacy stores, the direction and timing of water-quality responses, and response delays, helping models distinguish nutrient sources and reason about complex outcomes. It is suitable for reasoning fine-tuning, environmental science question answering, and analysis of nutrient pollution management scenarios.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| scenario_question | string | The original question asking how water quality might respond under a nutrient-loading counterfactual. |
| external_load_effect | string | Explanation of how changes in nutrients entering from external sources are expected to affect water quality. |
| counterfactual_answer | string | A concise, evidence-grounded answer describing the likely water-quality response to the intervention. |
| water_quality_response | string | Description of the expected direction and timing of changes in relevant water-quality outcomes, such as nutrient concentrations, algal growth, or oxygen conditions. |
| internal_loading_effect | string | Explanation of how nutrient release from sediments or other internal stores may affect water quality after the intervention. |
| response_lag_explanation | string | Explanation of why measurable water-quality improvement or deterioration may be delayed, including sediment release, stored nutrients, and ecosystem adjustment. |
| baseline_waterbody_context | string | Source information about baseline water quality, historical nutrient accumulation, sediment conditions, and relevant waterbody characteristics. |
| counterfactual_intervention | string | Source description of the proposed change, such as reducing external nutrient inputs or changing sediment nutrient release conditions. |
| causal_chain_and_uncertainty | string | Summary of the causal links connecting the intervention to the predicted response, together with relevant assumptions, uncertainty, and factors that could alter the outcome. |
| legacy_nutrient_store_effect | string | Explanation of how nutrients accumulated in the waterbody or sediments from past loading may continue to influence current conditions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

