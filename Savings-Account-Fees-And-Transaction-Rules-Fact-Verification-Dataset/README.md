---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Savings Account Fees and Transaction Rules Fact Verification Dataset
---

# Savings Account Fees and Transaction Rules Fact Verification Dataset

This dataset centers on savings account fee disclosures and account-rule web pages, pairing claims with source evidence and verification verdicts. It covers monthly fees, minimum balance requirements, transfer and withdrawal limits, and the applicable scopes and waiver conditions associated with those rules. By linking claims to amounts, currencies, account types, and exceptions, it supports training and evaluation of models for evidence retrieval, fact judgment, and explanation of financial rules.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| verdict | string | Conclusion about the claim based on the source text. |
| reasoning | string | Briefly explains how the evidence supports, refutes, or is insufficient to assess the claim, including how amounts, applicable scope, or exceptions correspond. |
| claim_text | string | A statement requiring verification about monthly fees, minimum balances, transfer or withdrawal limits, or waiver conditions. |
| source_url | string | URL of the source webpage; may be blank if it was not recorded. |
| source_text | string | Savings account fee disclosure or account-rule webpage text used to verify the claim. |
| rule_category | string | Category of account fee or transaction rule addressed by the claim. |
| evidence_quote | string | Key quotation from the source text that directly supports the verdict; may be blank if no relevant evidence is available. |
| applicable_scope | string | Account type, customer group, transaction type, or other conditions to which the rule applies. |
| amount_and_currency | string | Amount, currency, or balance threshold extracted from the rule; may be blank when no monetary information is provided. |
| exception_or_waiver | string | Waiver conditions, exceptions, and their requirements for the fee or restriction; may be blank when no relevant information is available. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

