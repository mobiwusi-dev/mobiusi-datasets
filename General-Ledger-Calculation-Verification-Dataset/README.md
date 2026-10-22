---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: General Ledger Calculation Verification Dataset
---

# General Ledger Calculation Verification Dataset

Covers company general ledger entries, account balances, and related calculation records, along with submitted results, correctness judgments, independently recomputed values, and error locations. It focuses on core financial calculations such as debit and credit totals, balance carryforwards, and account summaries, supporting the training and evaluation of models that verify calculation results and perform numerical reasoning. Typical uses include outcome checking, accounting review, and verifier development for enterprise financial management software.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| ledger_input | object | Original company ledger data used as the source for verification. |
| verification | object | Computed correctness judgment and classification for the submitted calculation. |
| error_locations | array | Specific calculation discrepancies and their locations in the submitted data. |
| recomputed_values | object | Values independently calculated from the original ledger input. |
| submitted_calculation | object | Calculation results provided for verification, including claimed totals and balances. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

