---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Strawberry Growth Stage and Phenological Attribute Extraction Benchmark
---

# Strawberry Growth Stage and Phenological Attribute Extraction Benchmark

Designed for web text in strawberry production, this benchmark contains original webpage content alongside annotations for growth stages, phenological states, observable features, stage transition cues, and supporting evidence spans. It focuses on descriptions of strawberry development and phenology, supporting the evaluation of models that identify plant status, extract attributes, and locate textual evidence in production materials. It can support agricultural information processing and domain-specific model evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| growth_stage | string | The strawberry growth stage explicitly stated or inferred from the source webpage. |
| evidence_spans | array | Quoted source passages supporting the extracted growth stage, phenological state, or observable features. |
| phenological_state | string | The specific phenological status described in the source, such as flowering, fruit set, or ripening. |
| observable_features | array | Visible or otherwise observable plant characteristics associated with the described growth stage or phenological state. |
| raw_webpage_content | string | The original HTML content of the strawberry production webpage used as the input source. |
| stage_transition_cues | array | Textual clues indicating a transition between strawberry growth stages or phenological states. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

