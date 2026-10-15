---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: PCT International-Phase Examination Document Retrieval Dataset
---

# PCT International-Phase Examination Document Retrieval Dataset

This dataset organizes international patent prosecution documents around examination questions arising during the PCT international phase, including international search reports, written opinions, international preliminary examination reports, applicant responses, amended claims, and procedural notices. Each record links a query with structured issue analysis, retrievable evidence units, legal bases, applicant response points, and relationships across documents. It supports the development and evaluation of patent-law RAG retrieval systems for evidence discovery, cross-document synthesis, and examination issue analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query | string | The original question, retrieval request, or legal analysis question concerning examination during the international phase. |
| answer_context | object | Consolidated context for downstream RAG generation or legal analysis, including a query summary, legal bases, key findings, and applicant response points. |
| query_analysis | object | Structured analysis derived from the original query, including the examination topic, legal issues, and procedural stage. |
| retrieval_units | array | Evidence passages extracted and organized from relevant legal documents for RAG retrieval, ranking, and response generation. |
| source_documents | array | Information about source documents relevant to the examination question, including international search reports, written opinions, international preliminary examination reports, applicant responses, amended claims, and procedural notices. |
| cross_document_links | array | Links among facts, conclusions, rules, and responses related to the same examination question across different PCT legal documents. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

