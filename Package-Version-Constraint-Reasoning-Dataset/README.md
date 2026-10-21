---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Package Version Constraint Reasoning Dataset
---

# Package Version Constraint Reasoning Dataset

This dataset presents software package declarations and version constraints from project manifests or configuration snippets, together with the resulting direct and transitive dependency relationships. Each example indicates whether the constraints can be satisfied simultaneously, identifies packages and declarations involved in any conflict, and provides a concise reasoning summary. It supports training and evaluation of models that analyze software dependency resolution problems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| conflict_details | array | Packages whose version constraints are incompatible, with the declarations responsible for each conflict. Use an empty array when no conflict is found. |
| dependency_edges | array | The resolved direct and transitive dependency relationships extracted from the manifest, with each edge recording its version constraint. |
| manifest_snippet | string | The original project manifest or configuration snippet containing package declarations and version constraints. |
| reasoning_summary | string | A concise explanation tracing relevant transitive dependencies and showing why the constraints are compatible, conflicting, or insufficient to determine a result. |
| resolution_status | string | Whether all dependency version constraints can be satisfied simultaneously. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

