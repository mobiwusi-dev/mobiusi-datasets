---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: M&A Due Diligence NDA Question Answering Dataset
---

# M&A Due Diligence NDA Question Answering Dataset

Focused on non-disclosure agreements used in mergers and acquisitions, investments, and due diligence, this dataset covers topics such as whether a transaction exists, target companies and affiliates, advisers and prospective investors, information access, and permitted transaction purposes. Each question and answer uses the agreement text as its closed knowledge source and includes supporting clause excerpts and an analysis of confidentiality obligations. It supports legal question answering, clause retrieval, and training and evaluation of models for specialized transaction contexts.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An answer grounded strictly in the NDA text, without adding facts or inferences beyond the agreement. |
| question | string | A question about a professional transaction context that the model must answer using the NDA text. |
| evidence_text | string | An excerpt or key clause from the agreement that supports the answer and identifies its textual basis. |
| agreement_text | string | The original text or content of an M&A, investment, or due diligence non-disclosure agreement, used as the closed knowledge source. |
| question_category | string | A category for the NDA topic addressed by the question, such as transaction existence, target companies and affiliates, advisers and prospective investors, information access, or transaction purpose. |
| confidentiality_analysis | string | A structured semantic analysis of confidentiality obligations, permitted information recipients, allowed purposes, or covered parties under the relevant agreement clauses. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

