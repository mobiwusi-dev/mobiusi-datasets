---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Procurement Spend Analysis Text-to-SQL Dataset
---

# Procurement Spend Analysis Text-to-SQL Dataset

This dataset pairs natural-language questions about procurement and spend analysis with relevant database schema context and SQL queries. Its analytical dimensions include suppliers, procurement categories, cost centers, time, and currencies, illustrating how business requests map to tables, columns, filters, and aggregation logic. It supports training and evaluation of text-to-SQL systems and SQL agents for procurement analytics and database tool use.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| sql_query | string | The SQL statement that answers the natural-language question using the provided database schema context. |
| database_schema_context | string | A JSON-formatted description of relevant spend records, dimension tables, columns, and relationships available to answer the question. |
| natural_language_question | string | The procurement or spend analytics request expressed in natural language. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

