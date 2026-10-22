---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: RF Circuit Fault Troubleshooting Document Retrieval Benchmark
---

# RF Circuit Fault Troubleshooting Document Retrieval Benchmark

This benchmark pairs RF circuit fault symptoms with relevant web-based troubleshooting guides, application notes, and technical documentation, covering issues such as abnormal gain, oscillation, mismatch, elevated noise, and unexpected power output. Each record includes a symptom query, source document, normalized fault category, relevance label, supporting passages, and retrieval rationale to help assess how useful a document is for diagnosing a specific issue. It is designed for technical information retrieval, relevance ranking, and fault analysis in RF system maintenance and debugging.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| symptom_query | string | The original description of an RF circuit issue, such as abnormal gain, oscillation, mismatch, elevated noise, or unexpected power output. |
| relevance_label | string | A judgment of how useful the source document is for diagnosing the symptom query. |
| source_document | object | The original source document and its identifying information, provided as a structured input. |
| symptom_category | string | The normalized primary RF fault category inferred from the symptom query. |
| retrieval_rationale | string | A concise explanation of how the document's guidance relates to the reported symptom and may help diagnose the fault. |
| supporting_passages | array | Passages from the source document that support its relevance to the reported RF circuit issue. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

