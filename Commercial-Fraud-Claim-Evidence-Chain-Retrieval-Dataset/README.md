---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial Fraud Claim Evidence-Chain Retrieval Dataset
---

# Commercial Fraud Claim Evidence-Chain Retrieval Dataset

This dataset brings together case documents, including complaints, motions, declarations, testimony excerpts, and exhibits, organized around commercial fraud elements such as misrepresentation, knowledge or intent, reliance, causation, and loss. For each specific fraud claim, retrieval requests are paired with supporting evidence drawn from related documents, with cross-document, multi-hop relationships preserved. It supports legal evidence retrieval, complex case analysis, and training or evaluation of knowledge-grounding capabilities.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_documents | array | Source documents forming the evidentiary basis of a case, including complaints, motions, declarations, testimony excerpts, and exhibits. |
| retrieval_queries | array | Original retrieval requests targeting specific commercial fraud claims and their legal elements. |
| retrieval_summary | object | A derived summary of element coverage, evidence completeness, and cross-document retrieval paths. |
| evidence_chain_results | array | Supporting evidence for each fraud element, extracted and organized from related documents in response to retrieval requests, with multi-hop relationships preserved. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

