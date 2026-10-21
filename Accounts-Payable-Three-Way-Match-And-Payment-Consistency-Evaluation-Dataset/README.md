---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Accounts Payable Three-Way Match and Payment Consistency Evaluation Dataset
---

# Accounts Payable Three-Way Match and Payment Consistency Evaluation Dataset

This dataset provides JSON records for purchase orders, goods receipts, supplier invoices, and payments, together with expected match outcomes, discrepancies, and evaluation summaries. Scenarios cover cross-record conflicts in quantities, amounts, supplier details, and document references, enabling evaluation of consistency checks in accounts payable workflows and supporting financial software testing and model evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| match_passed | boolean | Expected overall result indicating whether the records pass the defined three-way matching and payment consistency checks. |
| discrepancies | array | Ground-truth conflicts expected to be identified across the supplied records. |
| goods_receipt | object | Source goods receipt record provided as a JSON object. |
| payment_record | object | Source payment record provided as a JSON object. |
| purchase_order | object | Source purchase order record provided as a JSON object. |
| supplier_invoice | object | Source supplier invoice record provided as a JSON object. |
| evaluation_summary | string | Concise ground-truth summary of the expected consistency-check outcome. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

