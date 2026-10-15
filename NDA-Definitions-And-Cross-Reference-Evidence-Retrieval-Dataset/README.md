---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: NDA Definitions and Cross-Reference Evidence Retrieval Dataset
---

# NDA Definitions and Cross-Reference Evidence Retrieval Dataset

This collection covers non-disclosure agreements with defined terms, referential relationships, section cross-references, and exception references, paired with questions and evidence that require locating the source definition or related provisions. Agreement text retains section numbering and original paragraphs to support traceability across terms, provisions, and exceptions. It supports the development and evaluation of legal retrieval-augmented generation systems that retrieve complete supporting evidence from long documents and produce grounded answers.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_answer | object | The final response based on the agreement's definitions, cross-references, exception provisions, and supporting evidence. |
| defined_terms | array | Terms extracted from the agreement's definition provisions, including their definitions and original supporting evidence. |
| agreement_text | string | The complete non-disclosure agreement text to analyze, preserving section and clause numbering as well as the original paragraphs. |
| cross_references | array | Reference and cross-reference relationships between sections, clauses, or attachments in the agreement. |
| document_metadata | object | Basic document information extracted from the NDA text. |
| retrieval_question | string | A question that requires locating a definition source, related provision, cross-reference, or the scope of an applicable exception in the agreement. |
| retrieved_evidence | array | Complete legal text passages retrieved from the agreement and verified against the retrieval question. |
| exception_references | array | Provisions that limit, exclude, or override general definitions, obligations, prohibitions, or liability rules in the agreement. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

