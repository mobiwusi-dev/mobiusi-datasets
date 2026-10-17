---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Decorative Arts Museum Catalog Record Question Answering Dataset
---

# Decorative Arts Museum Catalog Record Question Answering Dataset

This dataset centers on collection catalog records from decorative arts museums and turns information such as object names, types, dates, creators, and collection details into closed-domain question-answering examples. Answers must rely strictly on the supplied record and identify supporting evidence; examples can also teach models to recognize when a record does not contain enough information. The data is suited to museum collection search, specialist question answering, and domain-model fine-tuning and evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise answer supported by the catalog record; state when the requested information is not recorded. |
| question | string | A question about the object that must be answered using only the supplied catalog record. |
| answerability | string | Whether the supplied catalog record contains enough information to answer the question. |
| catalog_record | object | The source catalog information used to answer the question. |
| supporting_evidence | string | The relevant catalog wording or a faithful reference to the record fields that support the answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

