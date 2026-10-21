---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Purchase and Sales Contract Claim Evidence Verification Dataset
---

# Purchase and Sales Contract Claim Evidence Verification Dataset

This dataset covers claims about parties, prices, quantities, delivery, payment, and other terms in purchase and sales contracts. Each claim is labeled as supported by the contract text, contradicted by it, or indeterminable from the available text, with reasoning and relevant evidence clauses. It supports training and evaluation of models that assess legal evidence sufficiency and connect verification judgments to contract language, as well as contract review and document analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reasoning | string | An explanation connecting the verification result to the wording and meaning of the contract. |
| claim_text | string | The claim about a party, price, quantity, delivery, payment, or another contract term that must be verified. |
| contract_text | string | The relevant text of the purchase or sales contract used as source evidence. |
| claim_category | string | The primary subject area of the claim. |
| evidence_items | array | The contract clauses or excerpts relevant to the claim and the relationship each bears to it. |
| verification_result | string | Whether the contract text supports the claim, contradicts it, or is insufficient to determine its accuracy. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

