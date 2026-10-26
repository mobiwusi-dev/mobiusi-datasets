---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Vertical Industry Enterprise Application Text-to-SQL Dataset
---

# Vertical Industry Enterprise Application Text-to-SQL Dataset

This dataset pairs natural-language business questions from vertical industry enterprise applications with relevant database schemas and corresponding SQL queries. The examples cover varied business data objects, table and column relationships, and industry-specific terminology, providing aligned supervision for translating business requests into structured queries. It supports enterprise analytics, natural-language database interaction, and the development and evaluation of SQL agents.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| target_sql | string | The SQL query corresponding to the business question and database schema, provided as the supervised target. |
| database_schema | object | The structured database schema relevant to answering the business question, including tables, columns, and relationships. |
| business_question | string | The natural-language request submitted by a user of a vertical enterprise application. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

