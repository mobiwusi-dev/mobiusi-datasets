---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: 5G Core Network Element State and Context Code Understanding Dataset
---

# 5G Core Network Element State and Context Code Understanding Dataset

This dataset centers on 5G core network source code involving network elements, user sessions, and related context objects. It provides code understanding tasks on object creation, initialization, updates, associations, state changes, and cleanup, with example answers grounded in cross-function code evidence. Its focus on object lifecycles and state management across functions supports model training and evaluation for core network software analysis, beyond tasks that only trace a single service call flow.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| task_prompt | string | A specific question and instructions for explaining an object's lifecycle or state changes. |
| lifecycle_actions | array | Operations summarized from the source logic, including object creation, initialization, updates, associations, state changes, and cleanup. |
| lifecycle_objects | array | Network elements, user sessions, and related context objects identified in the source code. |
| state_transitions | array | State changes inferred from the source code, including transition conditions, previous and resulting states, and related handling. |
| cleanup_conditions | array | Conditions that trigger the release, deletion, or cleanup of objects or context, along with the corresponding code paths. |
| source_code_context | string | Core network source code snippets for analysis, potentially spanning multiple functions, files, and related context. |
| cross_function_paths | array | Object handling paths across multiple functions, showing how objects and context are passed or modified between functions. |
| demonstration_answer | string | A complete explanation of object creation, updates, associations, state changes, and cleanup, supported by cross-function source code evidence. |
| object_relationships | array | How relationships between network elements, sessions, and context objects are established, maintained, or removed. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

