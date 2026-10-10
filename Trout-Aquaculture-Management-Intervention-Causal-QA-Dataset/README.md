---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Trout Aquaculture Management Intervention Causal QA Dataset
---

# Trout Aquaculture Management Intervention Causal QA Dataset

This dataset uses trout aquaculture management scenarios to build question-answer cases about interventions such as pond or tank separation, size grading, stocking-density adjustments, aeration, and water-flow management. Cases cover farming context, conditions and fish status before and after an intervention, observed outcome changes, concurrent adjustments, alternative explanations, and plausible outcomes without the intervention. It supports causal reasoning, counterfactual analysis, and aquaculture decision-making tasks in reasoning supervised fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct answer to the case question that integrates the intervention's possible effects, concurrent factors, alternative explanations, and a cautious estimate of the no-intervention scenario. |
| question | string | A causal or counterfactual question to be answered using the case material. |
| source_case | string | Unstructured case text containing the farming context, intervention process, observed outcomes, and related questions. |
| observed_outcome | string | A summary of key outcomes observed after the intervention, including their direction, magnitude, and time frame; explicitly note missing information. |
| causal_assessment | string | An assessment of whether the intervention may have caused the observed changes, explaining evidence that supports or limits the conclusion and distinguishing correlation from causation. |
| fish_status_after | string | The fish population's health, feeding, behavior, growth, or mortality after the intervention. |
| intervention_type | string | The primary aquaculture management intervention in the case, such as pond or tank separation, size grading, stocking-density adjustment, aeration, or water-flow adjustment. |
| concurrent_changes | string | Other management actions or environmental changes that occurred during the intervention period; if details are unavailable, state that they were not reported rather than assuming none occurred. |
| fish_status_before | string | The fish population's health, feeding, behavior, growth, or mortality before the intervention. |
| intervention_details | string | The intervention method, timing, scope, and intensity; state when details are unknown or not reported. |
| alternative_explanations | string | Other possible explanations for outcome changes, including concurrent adjustments, environmental fluctuations, disease, measurement error, or natural variation; state uncertainty when information is insufficient. |
| pre_intervention_conditions | string | A summary of relevant pre-intervention water quality, temperature, dissolved oxygen, flow rate, stocking density, and other production conditions. |
| post_intervention_conditions | string | A summary of relevant post-intervention changes in water quality, temperature, dissolved oxygen, flow rate, stocking density, and other production conditions. |
| counterfactual_without_intervention | string | A cautious estimate of how the fish population or production outcome might have changed without the intervention, with the basis, assumptions, and uncertainty stated. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

