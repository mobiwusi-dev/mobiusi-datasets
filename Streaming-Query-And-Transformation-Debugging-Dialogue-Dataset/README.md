---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Streaming Query and Transformation Debugging Dialogue Dataset
---

# Streaming Query and Transformation Debugging Dialogue Dataset

This dataset contains multi-turn conversations in which users progressively provide streaming SQL, transformation logic, error messages, and expected results, along with query fragments and assistant responses. It focuses on diagnosing syntax and logic issues in real-time data pipeline development, capturing an iterative workflow from clarifying context to proposing revisions. It is suited to dialogue supervised fine-tuning, streaming development assistant training, and evaluation of SQL debugging and query repair capabilities.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| messages | array | The transcript parsed into an ordered sequence of user and assistant messages. |
| sql_fragments | array | SQL snippets extracted from the dialogue for debugging, review, or revision. |
| resolution_status | string | The outcome reflected in the dialogue, such as a proposed fix or an unresolved issue. |
| diagnostic_summary | string | A concise summary of the suspected syntax or logic issue and its relevant context. |
| dialogue_transcript | string | The complete conversation, including user-provided SQL, transformation logic, errors, expected results, and assistant responses. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

