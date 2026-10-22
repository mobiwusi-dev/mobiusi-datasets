---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Financial Close JSON Consistency Evaluation Benchmark
---

# Financial Close JSON Consistency Evaluation Benchmark

This benchmark contains JSON vouchers, account balances, trial balance data, and financial statements from enterprise financial close workflows, with inconsistencies and supporting locations annotated across records. It focuses on checks between the general ledger and financial statements, debit and credit balances, and accounting-period data, enabling evaluation of a model's ability to detect and localize financial data inconsistencies. It is suitable for developing and automatically evaluating consistency-checking capabilities in enterprise financial management software.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| findings | array | Detailed inconsistency findings, including references to affected records and supporting JSON locations. |
| source_json | string | The original JSON payload containing financial-close vouchers, account balances, trial balance data, and financial statements, serialized as text. |
| is_consistent | boolean | Indicates whether the supplied financial records are consistent across the evaluated checks. |
| issue_categories | array | The categories of inconsistencies identified in the source data. |
| detected_issue_count | integer | The total number of distinct inconsistencies identified in the source data. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

