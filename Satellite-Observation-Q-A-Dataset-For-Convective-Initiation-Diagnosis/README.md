---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Satellite Observation Q&A Dataset for Convective Initiation Diagnosis
---

# Satellite Observation Q&A Dataset for Convective Initiation Diagnosis

This dataset turns meteorological satellite time-series clues, such as cloud development, cooling cloud tops, and localized cloud expansion, into diagnostic question-and-answer examples focused on possible triggers of new convection. Each record covers the observed clues, a diagnostic question, a possible mechanism, conclusions supported by the observations, unresolved factors, and the reasoning process, while distinguishing observations from inferences. It supports abductive reasoning research in satellite meteorology, reasoning SFT, model evaluation, and diagnostic Q&A system development.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| uncertain_factors | string | Lists factors that cannot be confirmed from the available satellite observations, possible alternative explanations, or evidence needed for further assessment. |
| diagnostic_question | string | Asks about possible convective triggering mechanisms based on the satellite observation clues. |
| diagnostic_reasoning | string | Explains how the time-series observation clues lead to a possible trigger mechanism and distinguishes observed facts from inferences. |
| supported_conclusions | string | Lists conclusions directly supported by the satellite observation clues and explains their evidential basis. |
| inferred_trigger_mechanism | string | States a possible mechanism for newly developing convection based on the clues, without presenting the inference as a confirmed fact. |
| satellite_observation_clues | string | Describes time-series satellite observations, including cloud development, cloud-top cooling, and localized cloud expansion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

