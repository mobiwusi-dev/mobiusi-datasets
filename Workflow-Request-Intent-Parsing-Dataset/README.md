---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Workflow Request Intent Parsing Dataset
---

# Workflow Request Intent Parsing Dataset

This dataset contains natural language requests to create or modify workflows, annotated with operation type, workflow goal, workflow objects, key parameters, and items requiring clarification. It covers common orchestration elements such as triggers, actions, conditions, and variables. The annotations support instruction tuning and help models convert workflow requests into structured intents for workflow assistants and related applications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| ambiguities | array | Ambiguities, missing information, or details that require confirmation from the user. |
| request_text | string | The original natural language request for creating or modifying a workflow. |
| workflow_goal | string | A summary of the outcome the user wants the workflow to achieve. |
| key_parameters | array | Workflow configuration parameters and values parsed from the request. |
| operation_type | string | The type of operation identified in the request. |
| workflow_objects | array | Triggers, actions, conditions, variables, or other workflow objects mentioned in the request. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

