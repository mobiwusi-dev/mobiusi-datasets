---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: ERP Master Data Consistency Evaluation Dataset
---

# ERP Master Data Consistency Evaluation Dataset

This evaluation dataset presents JSON records for ERP master data, including customers, suppliers, and products, alongside corresponding entries from other modules or business records. It labels duplicates, conflicts, and field-level mismatches, with consistency status, matched record keys, discrepancy annotations, and assessment summaries. Use it to evaluate models that match entities across records, detect data quality issues, and explain consistency findings, or to validate ERP data governance and auditing workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| discrepancies | array | The field-level duplicate, conflict, or inconsistency annotations for the assessed records. |
| is_consistent | boolean | Whether the records are consistent and do not contain a labeled duplicate, conflict, or field mismatch. |
| source_records | array | The original JSON records to compare, drawn from one or more ERP modules. |
| assessment_summary | string | A concise human-readable explanation of the gold consistency assessment. |
| consistency_status | string | The gold-standard classification of the relationship among the supplied records. |
| matched_record_keys | array | The record keys grouped together for the consistency assessment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

