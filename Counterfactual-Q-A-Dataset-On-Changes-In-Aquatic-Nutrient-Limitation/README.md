---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Counterfactual Q&A Dataset on Changes in Aquatic Nutrient Limitation
---

# Counterfactual Q&A Dataset on Changes in Aquatic Nutrient Limitation

Designed for nutrient pollution questions in lakes and other aquatic systems, this dataset contains counterfactual Q&A about baseline nitrogen and phosphorus conditions and changes in nutrient inputs, with key conditions held constant made explicit. Answers examine how nutrient limitation or co-limitation may shift and how those shifts could affect algal growth and water quality. The data supports training and evaluating models on mechanistic causal reasoning and aquatic environmental analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| algal_response | string | The predicted effect of the nutrient-input change on algal growth, abundance, or productivity. |
| key_assumptions | string | The assumptions and relevant conditions held constant that support interpretation of the counterfactual prediction. |
| scenario_prompt | string | The source scenario or question describing baseline nitrogen and phosphorus conditions, the nutrient-input change, and conditions held constant. |
| water_quality_effect | string | The predicted implications for water quality, such as changes in algal blooms, clarity, or oxygen conditions. |
| counterfactual_answer | string | A direct answer to the counterfactual question, stating the expected consequences of the specified nutrient-input change. |
| mechanistic_reasoning | string | The causal explanation linking nutrient availability and limitation status to the predicted algal and water-quality responses. |
| limitation_state_change | string | An analysis of how nutrient limitation or co-limitation is expected to change between the baseline and counterfactual conditions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

