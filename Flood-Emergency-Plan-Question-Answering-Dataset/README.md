---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Flood Emergency Plan Question Answering Dataset
---

# Flood Emergency Plan Question Answering Dataset

This dataset contains question-answer pairs based on flood emergency plans, response procedures, and operational guidance. Its procedural topics include warning thresholds, response responsibilities, action sequences, resource allocation, and conditions of applicability. Each record can link an answer to its reference passage and source document, with ordered steps included for sequence-based questions. It supports training and evaluating retrieval-augmented generation systems on retrieving and accurately restating emergency procedures from plan materials.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise answer grounded in the reference context and faithful to the source procedure. |
| question | string | A question about flood warnings, response responsibilities, action sequences, resources, or applicable conditions. |
| response_steps | array | The ordered actions required by the source procedure when the answer describes a sequence. |
| question_category | string | The primary topic of the question, such as warning thresholds, responsibilities, action order, or resource allocation. |
| reference_context | string | The source passage or retrieved plan content provided as evidence for answering the question. |
| supporting_evidence | string | A relevant quotation or paraphrase from the reference context that supports the answer. |
| source_document_name | string | The name of the emergency plan, procedure, or guidance document containing the reference context. |
| applicable_conditions | string | Thresholds, situations, locations, or other conditions that determine when the described guidance applies. |
| answerable_from_context | boolean | Whether the provided reference context contains sufficient information to answer the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

