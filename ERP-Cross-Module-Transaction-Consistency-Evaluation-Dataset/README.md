---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: ERP Cross-Module Transaction Consistency Evaluation Dataset
---

# ERP Cross-Module Transaction Consistency Evaluation Dataset

This evaluation dataset organizes related enterprise resource planning (ERP) order, shipment, invoice, and payment records in JSON, together with cross-module relationship and state constraints. It also provides expected inconsistencies and a consistency summary, enabling evaluation of a model's ability to detect missing records, conflicting information, and mismatched relationships. It is suitable for ERP data quality validation, business process audits, and automated evaluation of consistency-checking models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| transaction_records | object | Source ERP records grouped by module. Empty or absent module collections may indicate missing records. |
| consistency_constraints | array | Rules defining required relationships and state constraints across ERP modules. |
| expected_inconsistencies | array | Gold-standard discrepancies an evaluator should identify from the records and constraints. |
| gold_consistency_summary | object | A benchmark summary derived from the expected inconsistency labels. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

