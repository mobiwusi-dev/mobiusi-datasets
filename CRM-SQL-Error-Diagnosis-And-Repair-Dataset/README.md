---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: CRM SQL Error Diagnosis and Repair Dataset
---

# CRM SQL Error Diagnosis and Repair Dataset

This dataset is built around CRM query scenarios and pairs natural-language requirements with relevant database schemas or field definitions, flawed SQL, and error clues, along with corrected queries that satisfy the requirements and schema. Examples cover common issues such as mismatched field names, incorrect join keys, missing join conditions, and faulty aggregation logic, with an error category and repair explanation for each example. It supports training and evaluating agents that interpret CRM schemas, diagnose SQL errors, and generate correct queries.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| error_clues | string | Available clues about the SQL error, such as mismatched field names, incorrect join keys, missing join conditions, or faulty aggregation logic. |
| corrected_sql | string | The repaired SQL query that satisfies the request and is consistent with the provided CRM schema. |
| incorrect_sql | string | The SQL query containing one or more errors to diagnose and repair. |
| error_category | string | The primary error type identified during diagnosis. |
| schema_context | string | Relevant CRM schema or field definitions, preferably serialized as JSON, including table names, column names, data types, and relationships. |
| query_requirement | string | The natural-language CRM data request that the SQL query should satisfy. |
| repair_explanation | string | A concise explanation of the diagnosed error and the changes made to repair the SQL. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

