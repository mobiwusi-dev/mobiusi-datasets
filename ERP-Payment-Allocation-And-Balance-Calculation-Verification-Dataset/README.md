---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: ERP Payment Allocation and Balance Calculation Verification Dataset
---

# ERP Payment Allocation and Balance Calculation Verification Dataset

This dataset contains ERP invoice transaction records covering invoice amounts, currencies, multiple payment allocations, system-recorded allocation totals, and open balances, along with calculated values and correctness labels. The records support checks of allocation totals, remaining invoice balances, and overall balance status, helping identify numerical inconsistencies in transaction data. They are suitable for training and evaluating financial outcome verifiers, payment reconciliation workflows, and ERP data quality checks.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| currency | string | Currency code used for the invoice and its payment allocations. |
| invoice_amount | number | Original amount due on the invoice. |
| invoice_number | string | Unique reference for the invoice being settled. |
| payment_allocations | array | Individual payment amounts applied to the invoice. |
| recorded_open_balance | number | Unpaid invoice balance recorded by the ERP system. |
| calculated_open_balance | number | Invoice amount minus the sum of all individual payment allocations. |
| open_balance_is_correct | boolean | Whether the ERP-recorded open balance matches the invoice amount less allocated payments. |
| recorded_allocation_total | number | Allocation total recorded by the ERP system for comparison with the sum of individual allocations. |
| allocation_total_is_correct | boolean | Whether the ERP-recorded allocation total matches the sum of individual payment allocations. |
| calculated_allocation_total | number | Sum of all individual payment amounts allocated to the invoice. |
| overall_balance_verification_passed | boolean | Whether both the recorded allocation total and the recorded open balance are numerically correct. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

