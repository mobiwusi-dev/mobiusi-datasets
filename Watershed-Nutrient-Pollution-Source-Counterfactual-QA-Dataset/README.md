---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Watershed Nutrient Pollution Source Counterfactual QA Dataset
---

# Watershed Nutrient Pollution Source Counterfactual QA Dataset

This dataset provides counterfactual question-answer examples about nutrient sources in watersheds, including agricultural runoff and wastewater discharge. Examples describe baseline watershed and water-quality conditions, interventions that remove or change a source, relevant evidence, and comparative conclusions. Answers state assumptions, cautiously assess likely changes in nutrient levels and water quality, and identify evidence limits, supporting training and evaluation for environmental reasoning and water-quality impact analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | Asks how the specified source intervention would likely affect nutrient conditions or water quality compared with the baseline. |
| assumptions | string | States the assumptions required for the counterfactual comparison, such as other nutrient sources and environmental conditions remaining unchanged. |
| evidence_notes | string | Summarizes observations, studies, or other evidence relevant to the baseline and counterfactual comparison, including known limitations. |
| evidence_boundary | string | Explains what the available evidence supports and identifies uncertainty, missing information, or limits on causal attribution. |
| watershed_scenario | string | Describes the watershed, baseline conditions, relevant nutrient levels, and context needed to interpret the scenario. |
| source_intervention | string | Specifies the nutrient source removed or changed in the counterfactual scenario and any assumptions about the intervention. |
| counterfactual_answer | string | Compares the likely water-quality outcome under the counterfactual with the baseline using appropriately qualified language. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

