---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Claim Amendment Basis Retrieval Dataset
---

# Patent Claim Amendment Basis Retrieval Dataset

This dataset supports retrieval and legal argumentation concerning amendments to patent claims by linking claims, amendment explanations, examination opinions, and relevant text from application documents. Each sample organizes a natural language query, an analysis of the amendment, evidence passages and their supporting relationships, and summaries of the amendment basis, scope changes, and examination impact. It is designed for building and evaluating retrieval augmented generation systems for patent prosecution workflows. The data does not replace professional legal judgment; conclusions should be checked against the complete case record and applicable law.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| retrieval_query | string | A natural language question about the basis, scope change, legality, or examination impact of a claim amendment. |
| retrieval_answer | string | A summary for patent examination response workflows covering the amendment basis, scope changes, examination impact, and key citation locations. |
| source_materials | object | Claims, amendment explanations, examination opinions, and relevant legal text from application documents that provide the basis for retrieval and analysis. |
| evidence_segments | array | Original text passages relevant to the amendment or examination argument, along with their supporting relationships. |
| examination_impact | object | An analysis of how the amendment affects examination opinions, response strategy, and preparation of further evidence. |
| retrieval_keywords | array | Keywords or phrases for retrieving similar cases, legal grounds, and evidence passages. |
| modification_analysis | object | An analysis of the amendment type, changed technical features, affected claims, and issues that require evidentiary support. |
| legal_basis_assessment | object | An assessment, based on evidence passages, of whether the amendment has original support, exceeds the original disclosure, or is adequately reasoned. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

