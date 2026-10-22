---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Installment Finance Revenue and Unit Economics Reasoning Dataset
---

# Installment Finance Revenue and Unit Economics Reasoning Dataset

This dataset contains financial report records for durable consumer goods installment financing, including reporting period, product category, currency, loan originations and principal, as well as interest, fees, merchant subsidies, funding costs, and operating expenses. It provides calculation and interpretation examples for total revenue, total costs, net income, yields, and per-loan contributions, supporting analysis of profitability and cost structure. It is designed to train and evaluate numerical calculation, financial reasoning, and financial metric interpretation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| currency | string | The currency used for all monetary inputs and calculated amounts in the record. |
| net_income | number | Calculated as total revenue minus total costs. |
| total_costs | number | Calculated as funding cost plus operating expenses. |
| funding_cost | number | The cost of funding the installment portfolio during the reporting period, in the stated currency. |
| total_revenue | number | Calculated as interest income plus total fee income plus merchant subsidy income. |
| interest_income | number | Interest income recognized during the reporting period, in the stated currency. |
| late_fee_income | number | Late fee income recognized during the reporting period, in the stated currency. |
| product_category | string | The consumer product or installment financing category covered by the report. |
| reporting_period | string | The period covered by the financial report, expressed as a date range or standard period label. |
| total_fee_income | number | Calculated as origination fee income plus late fee income. |
| operating_expenses | number | Operating expenses allocated to the installment finance business for the reporting period, in the stated currency. |
| originations_count | integer | The number of installment loans originated during the reporting period. |
| principal_originated | number | The total principal amount originated during the reporting period, in the stated currency. |
| revenue_yield_percent | number | Calculated as total revenue divided by principal originated, multiplied by 100. This metric cannot be computed if principal originated is zero. |
| origination_fee_income | number | Origination and processing fee income recognized during the reporting period, in the stated currency. |
| merchant_subsidy_income | number | Subsidies paid by merchants and recognized as income during the reporting period, in the stated currency. |
| cost_per_originated_loan | number | Calculated as total costs divided by the number of originated loans. This metric cannot be computed if the number of originated loans is zero. |
| funding_cost_rate_percent | number | Calculated as funding cost divided by principal originated, multiplied by 100. This metric cannot be computed if principal originated is zero. |
| net_income_margin_percent | number | Calculated as net income divided by principal originated, multiplied by 100. This metric cannot be computed if principal originated is zero. |
| revenue_per_originated_loan | number | Calculated as total revenue divided by the number of originated loans. This metric cannot be computed if the number of originated loans is zero. |
| unit_economics_interpretation | string | A concise explanation of calculated revenue, costs, net income, yields, and per-loan contributions, including relevant caveats such as zero denominators. |
| net_income_per_originated_loan | number | Calculated as net income divided by the number of originated loans. This metric cannot be computed if the number of originated loans is zero. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

