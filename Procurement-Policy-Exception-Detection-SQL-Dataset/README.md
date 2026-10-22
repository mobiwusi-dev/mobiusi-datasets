---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Procurement Policy Exception Detection SQL Dataset
---

# Procurement Policy Exception Detection SQL Dataset

This dataset focuses on procurement controls and spend management, pairing natural-language questions with SQL queries and database schema information. It covers policy exception checks such as duplicate invoices, suspected split purchases, and purchases that bypass preferred procurement channels. Metadata describes exception categories, referenced tables and columns, detection logic, joins and aggregations, policy thresholds, and expected outcomes, supporting SQL Agent training and evaluation for procurement policy monitoring and risk review.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_sql | string | The original SQL query intended to identify or analyze the procurement policy exception. |
| query_pattern | string | The primary SQL analysis pattern used to implement the exception check. |
| source_question | string | The original natural-language question describing a procurement policy exception to detect. |
| policy_thresholds | string | Relevant procurement policy limits or threshold conditions expressed in the question or query. |
| referenced_tables | string | The database tables used by the SQL query, represented as a comma-separated list of table names. |
| exception_category | string | The primary procurement exception category addressed by the question and query. |
| referenced_columns | string | The key database columns used for filtering, joining, grouping, or comparison, represented as a comma-separated list. |
| source_database_schema | string | The source database schema and relevant table or column definitions, serialized as JSON text. |
| detection_logic_summary | string | A concise explanation of how the query identifies the targeted procurement exception. |
| expected_detection_outcome | string | A description of the records or conditions the query is expected to return. |
| join_and_aggregation_logic | string | A summary of the joins, grouping, counts, sums, or other aggregation operations used by the query. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

