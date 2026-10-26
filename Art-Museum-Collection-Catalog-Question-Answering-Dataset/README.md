---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Art Museum Collection Catalog Question Answering Dataset
---

# Art Museum Collection Catalog Question Answering Dataset

This dataset is built from collection catalog entries and related records from general art museums, covering details such as artwork titles, creators, dates, media, dimensions, and collection information. Each example includes a question, an answer grounded in the supplied records, and supporting evidence, making it suitable for training models to answer collection-related questions accurately and traceably within a closed body of museum knowledge.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise answer supported by the supplied records, without adding unsupported catalog information. |
| evidence | array | Source passages and references that substantiate the answer. |
| question | string | The question to answer using only the supplied catalog entries and related records. |
| source_records | array | Structured catalog entries and related records provided as source material for answering the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

