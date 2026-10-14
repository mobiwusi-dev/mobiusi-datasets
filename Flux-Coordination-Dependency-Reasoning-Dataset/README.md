---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Flux Coordination Dependency Reasoning Dataset
---

# Flux Coordination Dependency Reasoning Dataset

This dataset contains declarative YAML configurations for Flux resources such as GitRepository, Kustomization, and HelmRelease, including source references and dependency settings such as dependsOn, paired with reasoning questions and answers. It focuses on resource inventories, coordination dependency chains, topological ordering, and configuration change propagation in Flux GitOps workflows. Use it to train and evaluate models on Flux code understanding, dependency reasoning, and change impact analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| flux_manifests | string | Declarative Flux YAML source code containing GitRepository, Kustomization, and HelmRelease resources, along with their source references and dependsOn settings. |
| dependency_chain | array | A chain of object references ordered from prerequisite dependencies to downstream coordination objects. |
| dependency_order | array | The coordination order of Flux objects produced by topologically sorting their dependencies. |
| object_inventory | array | A list of Flux resource objects identified in the declarative source code, including their dependency and source reference information. |
| reasoning_answer | string | A complete answer to the reasoning question, covering object dependencies, coordination order, and configuration change propagation. |
| reasoning_question | string | A question about resource dependencies, coordination order, or configuration change propagation based on the provided Flux declarative source code. |
| config_change_propagation | object | An analysis of how a specified configuration change propagates through Flux object dependencies and source references. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

