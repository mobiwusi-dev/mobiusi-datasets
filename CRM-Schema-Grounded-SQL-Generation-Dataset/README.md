---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: CRM Schema-Grounded SQL Generation Dataset
---

# CRM Schema-Grounded SQL Generation Dataset

Each example links a CRM business request with table and field definitions retrieved through files or data tools, along with the corresponding SQL statement. Coverage includes common CRM entities such as accounts, contacts, leads, opportunities, and activities. The examples support training SQL agents to retrieve and use schema information when translating natural-language business questions into SQL, as well as evaluating and improving these capabilities.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| crm_schema | string | CRM table and field definitions, including relevant descriptions, provided as JSON-formatted schema context. |
| user_request | string | The natural-language CRM business request to be translated into SQL. |
| generated_sql | string | The SQL statement that answers the user request using the provided CRM schema. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

