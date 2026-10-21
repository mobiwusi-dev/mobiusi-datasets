---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: API Change Impact Analysis Dataset
---

# API Change Impact Analysis Dataset

This dataset presents software dependency graphs linking API definitions, shared components, endpoints, documentation, clients, and tests, alongside proposed code or specification changes. Each record can support identifying affected objects, tracing dependency paths, summarizing change impact, and recommending follow-up work. It is designed for change reviews, impact analysis, and regression test planning in API development.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| change_request | string | The source code change or specification change to analyze, provided as plain text, code, or a change description. |
| impact_summary | string | A concise overall explanation of the scope and consequences of the proposed change. |
| affected_objects | array | Objects inferred to be affected by the proposed change. |
| dependency_graph | string | The source API dependency graph serialized as JSON, including relevant definitions, shared components, endpoints, documentation, clients, tests, nodes, and edges. |
| dependency_paths | array | Dependency paths that explain how the proposed change reaches affected objects. |
| analysis_confidence | number | The model's confidence in the impact analysis, expressed as a value from 0 to 1. |
| recommended_actions | array | Suggested follow-up work, such as updating clients, documentation, or tests. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

