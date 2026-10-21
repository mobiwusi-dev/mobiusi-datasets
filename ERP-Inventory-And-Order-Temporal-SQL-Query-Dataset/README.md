---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: ERP Inventory and Order Temporal SQL Query Dataset
---

# ERP Inventory and Order Temporal SQL Query Dataset

This dataset covers business queries for enterprise resource planning (ERP) inventory and order management, including changes over time in stock levels, reserved quantities, batch details, and order statuses. Each example provides the relevant source-table schema and reference SQL, with a focus on time boundaries, historical point-in-time references, and status conditions. It supports training SQL agents to translate business questions into structurally accurate queries with appropriate temporal logic for inventory checks and order tracking.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_intent | string | A concise classification of the business objective, such as checking available stock or tracking order status. |
| reference_sql | string | The reference SQL query associated with the business question. |
| business_question | string | The natural-language ERP inventory or order-management question to be answered. |
| source_schema_sql | string | SQL DDL defining the source tables, columns, and relationships relevant to the question. |
| temporal_logic_summary | string | A summary of the time boundaries, historical reference points, and time-dependent conditions used by the query. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

