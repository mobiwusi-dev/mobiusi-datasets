---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Procurement Invoice Arithmetic Verification Dataset
---

# Procurement Invoice Arithmetic Verification Dataset

Contains procurement invoice transaction records, claimed amounts to verify, and arithmetic correctness labels covering quantity-times-unit-price calculations, line-item subtotals, discounts, taxes, shipping, and total due. By comparing claimed amounts with derived results and labeling overall correctness and error types, the data supports training and evaluating invoice calculation verifiers. Typical applications include invoice review, payment reconciliation, and financial automation in procurement and spend management.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| error_types | array | Unique arithmetic error classifications found in the invoice; an empty array indicates no errors. |
| invoice_checks | array | Derived comparisons for subtotal, discount, tax, and total due. |
| invoice_record | object | Raw invoice data, including line items, calculation inputs, and the amounts to be verified. |
| line_item_checks | array | Derived per-line comparisons of the claimed amount with quantity multiplied by unit price. |
| computed_subtotal | number | Sum of the expected line amounts, before discount, tax, and shipping. |
| computed_total_due | number | Computed subtotal minus computed discount plus computed tax and shipping amount. |
| overall_is_correct | boolean | Whether every line-item check and every invoice-level amount check is correct. |
| computed_tax_amount | number | Tax calculated from the pre-discount or post-discount taxable base specified in the raw invoice record, rounded to the currency's minor unit. |
| computed_discount_amount | number | Discount calculated as a percentage of the computed subtotal or as a fixed amount, capped at the subtotal and rounded to the currency's minor unit. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

