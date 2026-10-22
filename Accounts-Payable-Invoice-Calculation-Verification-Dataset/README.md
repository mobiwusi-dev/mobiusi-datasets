---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Accounts Payable Invoice Calculation Verification Dataset
---

# Accounts Payable Invoice Calculation Verification Dataset

Covers accounts payable invoices and line-item inputs such as quantities, unit prices, discounts, tax rates, tax amounts, and payable totals. It provides calculated subtotals, tax amounts, and payable totals, along with correctness labels and error categories. The records support line-level amount checks, discount and tax verification, invoice total reconciliation, financial numerical reasoning, and outcome verifier training.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| error_type | string | Primary category of any discrepancy between the stated and calculated amounts; use none when all amounts are correct. |
| invoice_inputs | object | Source data reported on the invoice and its line items. |
| calculated_subtotal | number | Subtotal computed as the sum of each line quantity multiplied by its unit price, less its discount. |
| calculated_tax_amount | number | Tax computed from the discounted taxable amount of each line and its tax rate. |
| is_calculation_correct | boolean | Whether the invoice's stated subtotal, tax amount, and payable total match the calculated values within the applicable currency rounding tolerance. |
| calculated_payable_total | number | Expected amount due computed as the calculated subtotal plus the calculated tax amount. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

