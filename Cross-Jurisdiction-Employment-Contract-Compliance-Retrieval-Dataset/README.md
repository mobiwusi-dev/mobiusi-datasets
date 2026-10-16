---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cross-Jurisdiction Employment Contract Compliance Retrieval Dataset
---

# Cross-Jurisdiction Employment Contract Compliance Retrieval Dataset

Designed for employment contract review across jurisdictions, this dataset organizes contract text, relevant labor laws and regulations, mandatory disclosure requirements, and compliance review questions. It annotates jurisdictional context, contract clauses, compliance findings, and legal authorities, with retrieval queries and evidence links to help systems find rules and source evidence relevant to specific clauses. It supports legal RAG retrieval, contract review assistance, and cross-jurisdiction compliance analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| is_compliant | boolean | An overall compliance determination for the sample based on its annotated contract clauses and legal authorities. |
| evidence_links | array | Traceable links among contract clauses, compliance findings, and legal authorities to support RAG retrieval and review explanations. |
| review_summary | string | A consolidated summary of the main compliance conclusions, risk points, and applicable legal authorities for the employment contract sample. |
| legal_citations | array | Statutory provisions, official guidance, and other authoritative sources associated with contract clauses or compliance findings. |
| retrieval_query | string | A query generated from the jurisdiction, contract clauses, compliance findings, and legal requirements to retrieve relevant rules and evidence in a RAG system. |
| contract_clauses | array | Searchable contract clauses segmented and normalized from the original employment contract. |
| raw_contract_text | string | The source text of the employment contract under review, preserving its original clauses and wording. |
| raw_legal_material | string | Source text of laws, regulations, administrative rules, mandatory disclosure requirements, or official interpretations relevant to the contract's jurisdiction. |
| compliance_findings | array | Compliance issues identified from the contract clauses and applicable legal requirements, including risk levels and analysis conclusions. |
| raw_review_question | string | The original question, retrieval intent, or compliance check requirement used to review the employment contract. |
| jurisdiction_context | object | Jurisdiction, governing law, and employment relationship context extracted from the contract and legal materials. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

