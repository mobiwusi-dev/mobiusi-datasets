---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: ERP Tax Calculation Verification Dataset
---

# ERP Tax Calculation Verification Dataset

The ERP Tax Calculation Verification Dataset focuses on enterprise transaction records, covering tax bases, applicable rates, tax-exempt and tax-inclusive indicators, recorded tax and transaction amounts, rounding rules, and expected results. Each record indicates whether the recorded tax and transaction total comply with the calculation rules. Use it to train outcome verifiers, check enterprise financial calculations, improve transaction-processing quality control, and evaluate numerical reasoning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| tax_rate | number | Applicable tax rate expressed as a decimal fraction, such as 0.2 for 20 percent. |
| is_tax_exempt | boolean | Indicates whether the transaction is tax exempt. If true, the expected tax amount is zero. |
| rounding_mode | string | Rounding rule used by the ERP to calculate monetary amounts. |
| tax_base_amount | number | Transaction amount used as the basis for tax calculation. For tax-inclusive transactions, it is the gross amount including tax; otherwise, it is the pre-tax amount. |
| is_tax_inclusive | boolean | Indicates whether the tax base amount already includes tax. This indicator is ignored for tax-exempt transactions. |
| rounding_precision | integer | Number of decimal places used to round calculated monetary amounts. |
| expected_tax_amount | number | Tax amount calculated from the tax base, rate, exemption and inclusion indicators, and specified rounding rules. |
| recorded_tax_amount | number | Tax amount stored in the ERP transaction record. |
| tax_amount_matches_rule | boolean | Indicates whether the recorded tax amount equals the expected tax amount after applying the specified rounding rules. |
| calculation_is_consistent | boolean | Indicates whether both the recorded tax amount and transaction total match their expected values. |
| expected_transaction_total | number | Transaction total calculated from the tax base and expected tax amount, accounting for whether tax is included or exempt. |
| recorded_transaction_total | number | Final transaction amount stored in the ERP record, including tax when applicable. |
| transaction_total_matches_rule | boolean | Indicates whether the recorded transaction total equals the expected transaction total after applying the specified rounding rules. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

