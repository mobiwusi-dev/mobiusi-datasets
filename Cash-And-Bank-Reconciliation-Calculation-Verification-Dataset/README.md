---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cash and Bank Reconciliation Calculation Verification Dataset
---

# Cash and Bank Reconciliation Calculation Verification Dataset

This dataset focuses on business cash ledgers, bank statements, and outstanding items. It includes ledger and bank balances, deposits in transit, outstanding payments, unrecorded bank credits and debits, and submitted reconciliation calculations and results. Adjusted balances, balance differences, and calculation and result validity indicators support checks of adjustment arithmetic, balance calculations, and reconciliation conclusions. It is designed for numerical reasoning, financial record verification, and outcome verifier training in enterprise financial management software.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| calculation_valid | boolean | Whether the submitted adjustment arithmetic agrees with the independently calculated amounts. |
| cash_book_balance | number | Balance calculated from the cash ledger records before reconciliation adjustments. |
| verification_notes | string | Concise explanation of calculation discrepancies, balance differences, or missing source information. |
| cash_ledger_records | string | Cash ledger entries and balances encoded as JSON text. |
| verification_status | string | Overall outcome of the reconciliation verification. |
| adjusted_bank_balance | number | Bank statement balance adjusted for deposits in transit and outstanding payments. |
| adjusted_book_balance | number | Cash book balance adjusted for unrecorded bank credits and debits. |
| bank_statement_balance | number | Balance extracted or calculated from the bank statement before reconciliation adjustments. |
| bank_statement_records | string | Bank statement entries and balances encoded as JSON text. |
| submitted_result_valid | boolean | Whether the reported reconciliation result agrees with the independently verified adjusted balances. |
| submitted_reconciliation | string | The proposed reconciliation process, calculations, and reported result encoded as JSON text. |
| deposits_in_transit_total | number | Sum of deposits recorded in the cash ledger but not yet shown on the bank statement. |
| outstanding_items_records | string | Deposits in transit, outstanding payments, and other unreconciled items encoded as JSON text. |
| outstanding_payments_total | number | Sum of payments recorded in the cash ledger but not yet cleared by the bank. |
| unrecorded_bank_debits_total | number | Sum of bank charges and other bank debits not yet recorded in the cash ledger. |
| reconciled_balance_difference | number | Absolute difference between the independently calculated adjusted bank balance and adjusted cash book balance. |
| unrecorded_bank_credits_total | number | Sum of bank credits not yet recorded in the cash ledger. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

