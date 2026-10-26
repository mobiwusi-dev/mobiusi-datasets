---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cross-Module Enterprise Finance Schema Linking and SQL Generation Dataset
---

# Cross-Module Enterprise Finance Schema Linking and SQL Generation Dataset

Covering enterprise finance modules such as general ledger, accounts payable, accounts receivable, suppliers, and customers, this dataset provides natural-language query requests, schema catalogs, relevant table selections, field mappings, join conditions, and target SQL. It focuses on cross-module schema understanding and query construction, helping train SQL agents to locate fields, select tables, and generate joined queries from business requirements. It is suitable for training and evaluating enterprise finance analytics, reporting queries, and data tool use.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| target_sql | string | The expected SQL query generated from the request and schema information. |
| user_request | string | The original natural-language request for a query spanning finance modules. |
| linked_fields | array | Schema fields mapped to the entities, filters, measures, and outputs requested by the user. |
| schema_catalog | string | Source documentation for relevant general ledger, accounts payable, accounts receivable, supplier, and customer tables and fields. |
| join_conditions | array | Relationships and join conditions needed to connect the selected tables. |
| selected_tables | array | Tables identified as relevant to answering the user request. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

