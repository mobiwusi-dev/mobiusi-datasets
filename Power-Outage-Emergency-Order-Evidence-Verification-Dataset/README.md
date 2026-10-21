---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Power Outage Emergency Order Evidence Verification Dataset
---

# Power Outage Emergency Order Evidence Verification Dataset

Focused on large-scale power outage response, this dataset contains excerpts from emergency declarations, administrative orders, and regulatory emergency orders, paired with legal and operational claims for verification. Annotations cover authorization, scope, effective duration, and designated actions, with judgments indicating support, contradiction, or insufficient evidence, along with relevant quotations, evidence locations, and rationales. It supports training and evaluating models for claim verification and evidence sufficiency assessment based on legal documents.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The claim about authorization, scope, effective duration, or a designated action to be evaluated against the document excerpt. |
| evidence_quote | string | The specific passage from the document excerpt that supports the verification judgment, or an empty string if no relevant passage can be identified. |
| claim_dimension | string | The legal or operational dimension addressed by the claim. |
| document_excerpt | string | The excerpt from an emergency declaration, administrative order, or regulatory emergency order to be evaluated. |
| evidence_locator | string | The available reference to the section, page, paragraph, or clause containing the quoted evidence. |
| judgment_rationale | string | A concise explanation of how the cited evidence supports, contradicts, or fails to determine the claim. |
| verification_label | string | Indicates whether the document excerpt supports, contradicts, or is insufficient to determine the claim. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

