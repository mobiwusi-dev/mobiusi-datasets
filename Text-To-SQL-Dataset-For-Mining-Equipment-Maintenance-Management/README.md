---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Text-to-SQL Dataset for Mining Equipment Maintenance Management
---

# Text-to-SQL Dataset for Mining Equipment Maintenance Management

This dataset pairs natural-language query requests with relational database schemas and corresponding SQL statements for mining equipment management. Its subject areas include equipment asset registers, maintenance work orders, downtime records, and spare-part usage. These examples support training models to translate operational questions into SQL for equipment maintenance data retrieval and analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| sql_query | string | The SQL statement corresponding to the natural-language request and database schema. |
| database_schema | string | The relational database schema, typically expressed as SQL DDL, for tables such as equipment assets, maintenance work orders, downtime records, and spare-part usage. |
| natural_language_query | string | The user's request for retrieving or analyzing mining equipment management data. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

