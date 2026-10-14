---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cache Consistency Protocol Code Reasoning Dataset
---

# Cache Consistency Protocol Code Reasoning Dataset

This benchmark focuses on implementation code for consistency protocols in distributed caching systems, covering cache read and write paths, version checks, leases, arbitration, and invalidation. Samples ask models to trace preconditions and dependencies among protocol components, state variables, and operations, then infer consistency guarantees, failure handling, and applicable boundaries. It supports code-reasoning model training, dependency analysis, and protocol behavior evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | Source code for the cache consistency protocol implementation to be analyzed. |
| read_write_paths | array | Cache read and write flows in the code, including version validation and consistency commit paths. |
| protocol_overview | string | A summary of the protocol's goals, core workflows, and consistency model. |
| state_dependencies | array | Precondition, read, update, and invalidation dependencies among protocol state variables. |
| analysis_conclusion | string | A final conclusion about consistency behavior and applicable boundaries, based on the protocol components, read and write paths, and state dependencies. |
| protocol_components | array | Protocol components identified in the code, such as caches, version management, leases, arbitration, and invalidation. |
| consistency_strategy | object | A summary of the implemented consistency mechanisms, guarantees, failure handling, and risks. |
| dependency_relations | array | Directed dependency relations among protocol components, states, and operations. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

