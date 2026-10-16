---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Employment Contract Claim Fact Verification Dataset
---

# Employment Contract Claim Fact Verification Dataset

This dataset pairs employment contract text with factual claims made about the contract and verification outcomes. It covers claims supported by the contract, contradicted by it, or not determinable from the text, with evidence spans, explanations, and evidence-sufficiency judgments. These annotations support training and evaluation of models that retrieve documentary evidence and verify statements against legal text.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | A factual statement about the employment contract that requires verification. |
| contract_text | string | The full text of an employment contract, serving as the source document for fact verification. |
| evidence_spans | array | Excerpts from the contract text used to support or contradict the claim; this may be an empty array when the claim cannot be determined. |
| verification_label | string | Indicates whether the claim is supported by the contract text, contradicted by it, or not determinable from it. |
| evidence_sufficiency | boolean | Indicates whether the extracted contract evidence is sufficient to clearly support or contradict the claim. |
| verification_explanation | string | A brief explanation of the assigned verification label based on the contract text and evidence spans. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

