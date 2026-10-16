---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Employment Contract Compensation Clause Fact Verification Dataset
---

# Employment Contract Compensation Clause Fact Verification Dataset

This dataset covers compensation provisions in employment contracts, including base pay, bonuses, commissions, equity, pay schedules, deductions, and reimbursements. Each record links a contract clause used as evidence with a compensation claim to verify, and may include amounts, currencies, payment conditions, eligibility requirements, a verification result, an evidence quote, normalized facts, and an explanation. It supports training and evaluating models that determine whether compensation claims are grounded in contract text, particularly when the contract does not specify the claimed information.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | Original text of a compensation-related factual claim to be checked against the contract clause. |
| claim_category | string | Category of the compensation provision addressed by the factual claim. |
| evidence_quote | string | Original contract excerpt that supports, contradicts, or contextualizes the claim; this may be empty when the contract makes no relevant provision. |
| normalized_fact | object | Structured compensation details extracted from the contract clause and claim, such as amount, currency, payment conditions, and eligibility requirements. Attributes that cannot be determined may be left blank. |
| verification_status | string | Result of checking the compensation claim against the contract clause; Not specified indicates that the contract does not provide sufficient evidence to support the claim. |
| contract_clause_text | string | Original employment contract text related to compensation, provided as evidence for verification. |
| verification_explanation | string | Explanation of how the contract clause supports, contradicts, or fails to support the claim, helping prevent unspecified information from being treated as a contractual fact. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

