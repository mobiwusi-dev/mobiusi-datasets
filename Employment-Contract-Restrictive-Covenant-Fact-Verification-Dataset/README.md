---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Employment Contract Restrictive Covenant Fact Verification Dataset
---

# Employment Contract Restrictive Covenant Fact Verification Dataset

This dataset focuses on restrictive commitments in employment contracts, supplementary agreements, and related legal documents, including confidentiality, intellectual property ownership, non-compete obligations, non-solicitation, and post-employment restrictions. It structures source text, verification claims, conclusions, evidence spans, and rationales, with attention to the obligated party, applicable period, territorial scope, and exceptions. It supports training and evaluation of models for evidence-based legal fact verification, employment compliance review, and legal document analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| exceptions | array | Circumstances, permitted activities, waiver conditions, or other exceptions to the restrictions specified in the document. |
| uncertainties | array | Elements of the restrictive commitment that are unspecified, ambiguous, or cannot be determined from the available evidence. |
| evidence_spans | array | Verbatim passages from the legal document, with locations where available, that support, contradict, or qualify the verification conclusion. |
| restriction_types | array | One or more categories of restrictive commitments identified from the document and the claim to verify. |
| territorial_scope | string | The geographic area covered by the restrictive commitment, such as a country, specified region, business area, or an unspecified scope. |
| obligation_subject | string | The party bound by the restrictive commitment, such as a worker, employee, company, or another specified party; state when the document does not specify it. |
| verification_claim | string | A specific claim about the existence, obligated party, or boundaries of a restrictive commitment that must be checked against the legal document. |
| verification_status | string | The fact verification conclusion reached for the claim based on the document evidence. |
| applicability_period | object | The time boundaries for the restrictive commitment, including its start, end, and any period continuing after employment ends. |
| evidence_sufficiency | string | An assessment of how sufficient the identifiable direct evidence in the document is for verifying the claim. |
| source_document_text | string | Full text of the employment contract, supplementary agreement, or related legal document used to verify the claim. |
| prohibited_activities | array | Activities expressly prohibited or limited by the document, such as working in an industry, conducting business, contacting clients, soliciting employees, or using information. |
| restriction_existence | boolean | Whether the restrictive commitment addressed by the claim is expressly present in the legal document. |
| verification_rationale | string | An explanation, grounded in the evidence spans, of why the claim is supported, partially supported, unsupported, or undetermined, without relying on generalizations beyond the document. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

