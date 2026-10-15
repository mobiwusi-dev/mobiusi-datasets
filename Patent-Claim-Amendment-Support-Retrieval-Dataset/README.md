---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Claim Amendment Support Retrieval Dataset
---

# Patent Claim Amendment Support Retrieval Dataset

This dataset contains amended claims, the original specification and claims, drawing descriptions, and written opinions from patent prosecution. It links individual amendment units to the original disclosure passages that may support them, with evidence chains, retrieval-ready chunks, passage locations, and an overall support judgment. The dataset supports amendment-basis review, legal document evidence retrieval, and the training and evaluation of retrieval-augmented generation systems for patent prosecution.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| amendment_units | array | Specific amendment units extracted and summarized from the amended claims. |
| retrieval_chunks | array | Evidence chunks segmented from the original disclosure documents for RAG retrieval, with passage location information retained. |
| support_evidence | array | Links each specific amendment unit to supporting passages in the original specification, original claims, drawing descriptions, or written prosecution opinions. |
| support_judgment | object | An aggregate judgment on whether all amendments are supported by the original disclosure. |
| amended_claims_text | string | The full text of the amended claims to be reviewed. |
| office_opinions_text | string | Relevant written opinions from prosecution, including office actions, notices to correct, applicant statements, and other written communications. |
| original_claims_text | string | The full text or searchable text of the claims as filed. |
| drawing_description_text | string | Descriptions of the drawings in the original application and related textual disclosures. |
| original_specification_text | string | The full text or searchable text of the specification as filed, including detailed embodiments, the summary of the invention, and relevant passages. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

