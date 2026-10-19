---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Closed-Campus HD Map Connectivity Reasoning Dataset
---

# Closed-Campus HD Map Connectivity Reasoning Dataset

This question-answer dataset covers road, lane, intersection, and topological connection facts for closed-campus environments. Each sample can include map facts, a connectivity question, a reachability label, an ordered path-node sequence, a reasoning trace, and a natural-language answer. It supports reasoning SFT and evaluation of reachability judgments, path existence, and multi-hop connectivity inference from HD map topology.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | A question about the map facts, such as node reachability, path existence, or a multi-hop connection. |
| map_facts | string | Topology facts about campus roads, lanes, intersections, and their connections, provided as JSON text or another structured text format. |
| reasoning | string | Explains how the connectivity conclusion follows from the nodes and connections in the map facts. |
| path_nodes | array | Lists the road, lane, or intersection nodes along the path in travel order when a path exists; an empty array indicates no path. |
| answer_text | string | A user-facing natural-language answer summarizing the connectivity conclusion and relevant path information. |
| is_reachable | boolean | Indicates whether a feasible connecting path exists between the nodes referenced in the question, based on the map topology. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

