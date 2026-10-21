---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Installment Receivables Credit Loss Numerical Reasoning Dataset
---

# Installment Receivables Credit Loss Numerical Reasoning Dataset

Built around financial reports on consumer installment receivables, this dataset provides structured information and expert analysis examples covering aging, defaulted balances, charge-offs and recoveries, credit loss allowances, and period changes. Examples address calculations such as loss rates, net charge-off rates, and allowance roll-forward reconciliations, helping models learn to extract figures, apply formulas, and explain results. It is suited to consumer finance credit risk analysis, financial data understanding, and domain-specific model fine-tuning and evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| recoveries | number | Amounts collected during the reporting period on receivables previously written off. |
| currency_code | string | Currency code for reported monetary amounts, such as USD. |
| reporting_period | string | Reporting period extracted from the source report. |
| closing_loss_rate | number | Closing loss allowance divided by total gross receivables as of the reporting date. |
| defaulted_balance | number | Balance identified as defaulted during the reporting period or at the reporting date, according to the source data. |
| gross_charge_offs | number | Receivables written off as uncollectible during the reporting period, before recoveries. |
| past_due_1_30_days | number | Receivables that are 1 to 30 days past due as of the reporting date. |
| analysis_conclusion | string | Concise interpretation of the aging profile, credit loss performance, allowance adequacy, and reconciliation results. |
| current_receivables | number | Receivables that are not past due as of the reporting date. |
| net_charge_off_rate | number | Gross charge-offs less recoveries, divided by average gross receivables for the period. |
| past_due_31_60_days | number | Receivables that are 31 to 60 days past due as of the reporting date. |
| past_due_61_90_days | number | Receivables that are 61 to 90 days past due as of the reporting date. |
| calculation_reasoning | string | Step-by-step explanation of extracted inputs, formulas, calculations, and assumptions. |
| credit_loss_provision | number | Provision recognized during the reporting period to adjust the loss allowance. |
| past_due_over_90_days | number | Receivables that are more than 90 days past due as of the reporting date. |
| closing_loss_allowance | number | Loss allowance balance at the end of the reporting period. |
| opening_loss_allowance | number | Loss allowance balance at the beginning of the reporting period. |
| total_gross_receivables | number | Total gross receivables as of the reporting date, before the loss allowance is deducted. |
| financial_report_excerpt | string | Source text from the financial report used for the analysis. |
| average_gross_receivables | number | Average gross receivables over the period, used as the denominator for the period-based net charge-off rate. |
| allowance_reconciliation_difference | number | Difference between the calculated and reported closing allowances, using opening allowance plus provision less gross charge-offs plus recoveries. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

