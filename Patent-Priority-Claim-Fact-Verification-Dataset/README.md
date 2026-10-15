---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Priority Claim Fact Verification Dataset
---

# Patent Priority Claim Fact Verification Dataset

This dataset pairs factual claims about patent priority applications, priority dates and jurisdictions, continuation applications, and divisional relationships with evidence bundles. The evidence includes web-based bibliographic information, priority data, and application relationship records, alongside structured claim facts, support labels, evidence excerpts, and verification explanations. It supports training and evaluating models that check patent relationship statements against evidence, with applications in patent prosecution, search, and legal technology.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | A factual statement to verify about patent priority, continuation, or divisional relationships. |
| claim_facts | object | Structured facts extracted from the claim, such as application numbers, dates, jurisdictions, and application relationships. |
| evidence_bundle | object | Web-based bibliographic information, priority data, and application relationship records used to verify the claim. |
| confidence_score | number | The model's confidence in the verification status, expressed as a value from 0 to 1. |
| evidence_support | boolean | Indicates whether the evidence supports the core factual relationships stated in the claim. |
| supporting_evidence | array | Text excerpts located in the evidence bundle that support or contradict factual elements of the claim. |
| verification_status | string | A classification of the degree of support between the claim and the evidence. |
| verification_explanation | string | An explanation of the verification result based on the claim facts and evidence text. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

