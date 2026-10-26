---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cyber Incident Claims Evidence Sufficiency Verification Dataset
---

# Cyber Incident Claims Evidence Sufficiency Verification Dataset

This dataset pairs specific cyber insurance claims with case-file materials, including claim statements, formal reports, correspondence, and other relevant documents, and labels whether the documents adequately support each claim. Annotations include supporting evidence passages, unsupported claim elements, and explanations of evidentiary gaps. It is designed to train and evaluate evidence verifiers and to help reviewers trace decisions and identify missing support in cyber incident claims.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_statement | string | The specific cyber insurance claim being evaluated for evidentiary support. |
| case_file_documents | string | Text from the case file for review, including formal reports, correspondence, and other relevant legal or claims documents. Preserve document boundaries and headings where possible. |
| is_evidence_sufficient | boolean | Indicates whether the provided case-file documents sufficiently support the specific claim. |
| insufficiency_explanation | string | A concise explanation of material evidentiary gaps or limitations. If the evidence is sufficient, state that no material insufficiency was identified. |
| unsupported_claim_elements | array | Specific claim elements that are not adequately supported by the provided documents. Leave empty when no material elements are unsupported. |
| supporting_evidence_passages | array | Relevant quoted passages that support or materially qualify the assessment. Include the document name and a page, section, or paragraph locator when available. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

