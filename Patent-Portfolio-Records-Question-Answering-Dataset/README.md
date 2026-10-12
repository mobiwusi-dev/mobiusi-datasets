---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Portfolio Records Question Answering Dataset
---

# Patent Portfolio Records Question Answering Dataset

This dataset provides closed-domain question-answering examples grounded in patent applications, granted patent texts, and portfolio records, with expert answers and supporting documentary evidence. Its topics include patent families, priority claims, claims, legal status, and geographic coverage; structured portfolio facts and scope notes help trace answer support and identify information that is absent or cannot be confirmed from the documents. It is designed for domain-specific fine-tuning, closed-document QA evaluation, and queries about portfolio composition and recorded facts.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An accurate, clear answer to the user question, limited to facts recorded in the source documents. |
| evidence | array | Source document references, supporting excerpts, and the corresponding fact categories. |
| question | string | A patent portfolio management question that must be answered using the supplied source documents. |
| scope_note | string | A note describing the document scope behind the answer, missing information, or matters that cannot be confirmed from the available documents. Omit when no note is needed. |
| portfolio_facts | object | Patent portfolio facts derived from the source documents. Include only information explicitly supported by the documents; omit anything that cannot be confirmed. |
| source_documents | array | Patent application texts, granted patent texts, or portfolio records used to support the answer. Each record corresponds to one document. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

