---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Trout Aquaculture Water Quality Causal Diagnosis QA Dataset
---

# Trout Aquaculture Water Quality Causal Diagnosis QA Dataset

This dataset organizes question-answer cases about dissolved oxygen, temperature, ammonia nitrogen, nitrite, and water flow in trout ponds and water supply systems. Cases include source records, event timelines, fish responses, and management actions to help models examine possible links between water quality changes and stress, reduced feeding, or mortality. It supports water quality event diagnosis, aquaculture management assistance, and training or evaluation of causal reasoning QA models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_question | string | A water quality event diagnosis question based on the source material in the case. |
| evidence_gaps | string | Missing evidence needed to confirm causal relationships, such as insufficient measurement frequency, missing key indicators, unclear event order, unexcluded alternatives, or interventions whose effects cannot be isolated. |
| fish_response | string | A summary of trout responses such as stress, abnormal swimming, reduced feeding, illness, or mortality, including their timing. |
| possible_causes | string | Possible water quality changes or management factors that may have contributed to fish responses, with their rationale based on case evidence and without presenting correlation as proven causation. |
| raw_case_record | string | Source evidence for the case, including water quality measurements from the pond and water supply system, the event timeline, fish responses, and management records. |
| causal_mechanism | string | An explanation of how changes in dissolved oxygen, temperature, ammonia nitrogen, nitrite, or water flow may lead to trout stress, reduced feeding, or mortality, including event order and possible pathways. |
| timeline_summary | string | A chronological summary of changes in dissolved oxygen, temperature, ammonia nitrogen, nitrite, water flow, fish responses, and management actions. |
| diagnostic_answer | string | A comprehensive answer to the original question that distinguishes possible causes from accompanying phenomena and explains mechanisms, evidence strength, and limits on causal conclusions. |
| management_actions | string | A summary of actions taken in the case, such as aeration, water exchange, feeding adjustments, cleaning, or other interventions, with their timing. |
| water_quality_changes | string | A summary of the direction, magnitude, duration, and timing of changes in water quality indicators and water flow, noting missing or uncertain measurements. |
| accompanying_phenomena | string | Water quality changes, fish behaviors, or management events that occurred alongside possible causes but cannot yet be identified as causal. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

