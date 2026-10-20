---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Buy Now Pay Later Credit Performance Claim Verification Dataset
---

# Buy Now Pay Later Credit Performance Claim Verification Dataset

Focused on credit performance disclosures in Buy Now Pay Later (BNPL), this dataset organizes claims about delinquencies, bad debts, write-offs, provisions, and receivables alongside supporting tables, notes, and text from financial reports. Records capture metric names and values, reporting periods, portfolio scopes, alignment between definitions and reporting context, and verification outcomes of supported, contradicted, or unconfirmed. It supports training and evaluation of models that verify credit risk claims in financial reports, including cases where metric definitions, periods, or portfolio scopes do not align.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The original claim about BNPL delinquencies, bad debts, write-offs, provisions, or receivables that requires verification. |
| confidence | number | A score indicating the reliability of the verification outcome, ranging from 0 to 1. |
| metric_name | string | The credit performance metric identified in the claim, such as a delinquency rate, write-off amount, or receivables. |
| claimed_value | string | The metric value or qualitative result stated in the claim, preserving the original wording and unit. |
| claimed_period | string | The reporting period or measurement date covered by the claim. |
| evidence_quote | string | A relevant excerpt from the report supporting the verification outcome; leave blank when no usable excerpt is available. |
| reported_value | string | The corresponding metric value or qualitative result identified in the financial report evidence, preserving the original wording and unit. |
| reported_period | string | The reporting period or measurement date covered by the evidence. |
| verification_status | string | Indicates whether the claim is supported by the reported data, contradicted by it, or unconfirmed due to insufficient evidence. |
| report_evidence_text | string | The original text of a relevant table, note, or passage from a financial report. |
| period_scope_alignment | string | Describes whether the claim and report evidence use matching periods and portfolio scopes, including any limitations on comparison. |
| verification_rationale | string | Explains the verification outcome using the values, metric definitions, periods, and portfolio scopes. |
| claimed_portfolio_scope | string | The product, customer, geographic, or asset portfolio scope covered by the claim. |
| reported_portfolio_scope | string | The product, customer, geographic, or asset portfolio scope covered by the report evidence. |
| metric_definition_alignment | string | Describes whether the metric definitions in the claim and report evidence match, and identifies any differences. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

