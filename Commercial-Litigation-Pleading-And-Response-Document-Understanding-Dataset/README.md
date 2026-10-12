---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial Litigation Pleading and Response Document Understanding Dataset
---

# Commercial Litigation Pleading and Response Document Understanding Dataset

This dataset covers complaints, answers, and counterclaims used in commercial litigation, pairing source document text with structured understanding annotations. Its fields capture parties, assertions, case facts, disputed issues, admissions or denials, and requests for relief, supporting the extraction of key information and interpretation of pleading semantics. It is suitable for legal document understanding, litigation information extraction, and domain-specific model fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| facts | array | Case facts extracted from the document, including related dates or time information. |
| parties | array | Parties identified in the document and their roles in the litigation. |
| document_type | string | Identifies the document category, such as a complaint, answer, or counterclaim. |
| disputed_issues | array | Disputed points or matters in the document that may require adjudication. |
| relief_requests | array | Claims for relief or other remedies requested from the court in the document. |
| party_assertions | array | Assertions in the document, extracted and associated with the party making each assertion. |
| admissions_denials | array | A party's admissions, denials, or other responses to the opposing party's assertions or case facts. |
| source_document_text | string | The original text of a complaint, answer, or counterclaim. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

