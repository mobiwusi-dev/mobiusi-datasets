---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Highway HD Map Lane Connectivity Reasoning Dataset
---

# Highway HD Map Lane Connectivity Reasoning Dataset

This dataset provides question-answer examples built around highway HD map lane segments and their predecessor, successor, and connection relationships. Samples cover reachability checks for specified lanes or road exits and inference of connecting paths, with topology data, questions, step-by-step reasoning, reachability results, paths, and concise answers. It supports reasoning supervised fine-tuning, map connectivity question answering, and evaluation of models for autonomous driving maps.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reasoning | string | A step-by-step explanation of the connectivity inference based on the provided lane topology. |
| final_answer | string | A concise natural-language response to the connectivity question. |
| is_reachable | boolean | Indicates whether the queried destination is reachable through the lane connectivity graph. |
| lane_topology | string | High-definition map lane segments and their predecessor, successor, and connection relationships, serialized as JSON. |
| connection_path | array | The ordered identifiers of lane segments along a valid connection path, or an empty list if no path exists. |
| connectivity_question | string | A question identifying the lane or road exit to evaluate and asking whether it is reachable. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

