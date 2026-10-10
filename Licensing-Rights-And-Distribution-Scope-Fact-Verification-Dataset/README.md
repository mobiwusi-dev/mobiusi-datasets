---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Licensing Rights and Distribution Scope Fact Verification Dataset
---

# Licensing Rights and Distribution Scope Fact Verification Dataset

This dataset organizes claims, supporting contractual evidence, and verification outcomes concerning licensed products, territories, sales channels, customer scope, exclusivity, and sublicensing rights in licensing and distribution agreements. Structured records cover contract text, claim scope, rights actually granted, contractual restrictions, and verification rationale, making the basis for each assessment easier to trace. It is designed for training and evaluating legal text fact-verification models, as well as supporting contract review and rights-scope analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence | array | Contract quotations and location information used to assess whether the claim matches the actual contractual terms. |
| claim_text | string | A claim about licensing rights or distribution scope to be assessed against the contract text. |
| claim_scope | object | Products, territories, channels, customers, and rights conditions extracted from the claim to verify. |
| restrictions | array | Restrictions, exceptions, and applicable scope conditions imposed by the contract on licensing or distribution rights. |
| contract_text | string | The original licensing or distribution agreement text used as the basis for verification. |
| contractual_scope | object | The licensing or distribution rights actually granted by the contract, summarized with their boundaries. |
| verification_result | string | The factual determination made about the claim based on the contract text. |
| verification_rationale | string | The reasoning behind the verification result, based on the rights granted or restricted by the contract and the supporting evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

