---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cache Shard Routing Dependency Reasoning Dataset
---

# Cache Shard Routing Dependency Reasoning Dataset

This dataset focuses on source code for distributed cache routing, including hash sharding, slot mapping, node selection, redirection, and shard migration, paired with structured reasoning annotations. Examples identify routing data structures, execution control flow, and dependencies among variables, functions, and branches, then analyze request routes and the effects of node or mapping changes. It supports training and evaluation of code understanding, dependency tracing, and change-impact reasoning for cache routing.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | Source code containing logic for hash sharding, slot mapping, node selection, redirection, or shard migration. |
| control_flow | array | Steps in execution order, from processing the request key through node selection and any redirection or migration handling. |
| change_impact | array | Inferred effects of changes to nodes, slot mappings, or migration state on request paths and routing outcomes. |
| evidence_spans | array | Source code locations that support identification of routing data structures, control flow explanations, and impact inferences. |
| route_decision | object | The inferred route for a single request, from its key to the final node, based on the source code. |
| dependency_graph | array | Dependencies among variables, functions, data structures, and control branches involved in routing decisions. |
| inference_summary | string | An overall summary of routing dependencies, request paths, and the effects of node or mapping changes. |
| routing_data_structures | object | Routing-related data structures identified and summarized from the source code. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

