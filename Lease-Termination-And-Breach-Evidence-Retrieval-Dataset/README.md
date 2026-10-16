---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lease Termination and Breach Evidence Retrieval Dataset
---

# Lease Termination and Breach Evidence Retrieval Dataset

This dataset pairs retrieval questions with legal document text and structured annotations covering lease breach determinations, cure periods, termination rights, early termination, damages, and notice procedures. It includes target legal issues, supporting evidence spans, structured assessments, and concise answer summaries across document types such as contracts, judgments, rulings, pleadings, and notices. It supports training and evaluation of evidence retrieval and grounding in legal retrieval-augmented generation, as well as contract review and case research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query_text | string | The original retrieval question about lease breach determinations, cure periods, termination rights, early termination, damages, or notice procedures. |
| target_issues | array | Legal issues inferred from the query and source document that need to be retrieved or assessed. |
| answer_summary | string | A concise summary of the key evidence, the breach or termination conclusions it supports, and any remaining uncertainty. |
| evidence_spans | array | Text spans extracted from the legal document that directly or partially support an assessment of breach, termination, or related legal elements. |
| damages_assessment | object | Extracted and summarized claims and supporting grounds for damages related to breach or early termination. |
| source_document_text | string | The text of a lease, judgment, ruling, pleading, notice, or other relevant legal document to be searched. |
| notice_cure_assessment | object | Extracted facts and legal analysis concerning termination notices, breach notices, and cure periods. |
| termination_assessment | object | A structured assessment, based on retrieved evidence, of whether a breach occurred, whether a termination right exists, and whether termination is effective. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

