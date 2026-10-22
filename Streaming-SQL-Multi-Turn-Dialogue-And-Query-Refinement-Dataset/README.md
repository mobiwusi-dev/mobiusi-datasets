---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Streaming SQL Multi-Turn Dialogue and Query Refinement Dataset
---

# Streaming SQL Multi-Turn Dialogue and Query Refinement Dataset

This dataset contains multi-turn text conversations in which users describe streaming analytics needs, add constraints, and iteratively refine SQL queries. It covers streaming concepts such as windowing, time semantics, and aggregation, with records that can include the full transcript, requirement and clarification summaries, the final query, SQL dialect, and revision history. It supports training models to interpret requirements through dialogue, generate streaming SQL, and revise queries based on feedback.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| sql_dialect | string | The streaming SQL dialect or engine identified or assumed for the final query, when available. |
| final_sql_query | string | The final streaming SQL query produced or revised during the conversation, including relevant windowing and time semantics. |
| clarification_summary | string | A summary of ambiguities identified and clarified during the conversation, including the resulting decisions. |
| query_revision_summary | string | A summary of how the SQL query changed across iterations and which user-provided constraints motivated those changes. |
| streaming_sql_features | string | A concise list of streaming concepts used or requested, such as event time, watermarks, windows, joins, state, and aggregations. |
| conversation_transcript | string | The complete original conversation, preserving turn order and the user's requests, constraints, clarifications, and assistant responses. |
| conversation_turn_count | integer | The number of conversational turns represented in the original transcript. |
| user_requirements_summary | string | A concise summary of the analytics goal, requested outputs, and explicit user constraints derived from the conversation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

