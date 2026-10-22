---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Supply Chain SQL Generation Hard-Case Dataset
---

# Supply Chain SQL Generation Hard-Case Dataset

This dataset contains natural-language questions and SQL examples that are prone to errors in supply chain database queries, covering pitfalls such as join fan-out, missing-value handling, temporal boundaries, and mismatched business grains. Each example pairs a database schema with reference SQL and optional business context to help models interpret intent and generate queries that respect both the schema and business rules. It supports supervised SQL Agent training, text-to-SQL evaluation, and query error analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_text | string | The original business question that the SQL query is expected to answer. |
| reference_sql | string | The vetted SQL query that correctly answers the natural-language question against the supplied schema. |
| database_schema | string | The source database schema, including relevant tables, columns, and relationships, represented as SQL DDL or equivalent schema text. |
| business_context | string | Optional domain definitions, metric rules, or other business assumptions needed to interpret the query correctly. |
| join_fanout_risk | boolean | Indicates whether joins across tables could duplicate rows and inflate counts or aggregates if handled incorrectly. |
| failure_mechanism | string | A concise explanation of how a plausible but incorrect query could produce an erroneous result. |
| business_grain_note | string | An explanation of the intended business entity or aggregation grain and any mismatch that must be resolved. |
| hard_case_categories | array | Derived labels for the semantic or structural pitfalls addressed by the example. |
| missing_value_handling | string | Guidance on how null or otherwise missing values should be treated for the query, or an indication that no special handling is needed. |
| temporal_boundary_rule | string | Guidance on relevant date or time filters, including boundary inclusivity and interval interpretation, or an indication that no temporal boundary applies. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

