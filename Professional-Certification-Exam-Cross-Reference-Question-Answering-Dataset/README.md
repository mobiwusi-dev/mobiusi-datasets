---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Professional Certification Exam Cross-Reference Question Answering Dataset
---

# Professional Certification Exam Cross-Reference Question Answering Dataset

Designed for professional certification exam questions that require information from multiple sources, this dataset provides questions, reference materials such as exam textbooks and regulations, synthesized answers, reasoning notes, and supporting evidence with source locations. By bringing together knowledge scattered across documents, it supports the development and evaluation of retrieval-augmented systems that answer with verifiable evidence. Typical uses include open-book question answering, multi-document retrieval, and evidence-grounded response generation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A synthesized answer based on information from the supplied reference materials. |
| evidence | array | The specific source passages and locations that substantiate the answer. |
| question | string | The original professional examination question to be answered using the supplied reference materials. |
| reference_materials | array | Source materials available for answering the question, including relevant content and source-location details. |
| synthesis_rationale | string | A concise explanation of how information from multiple references was combined to produce the answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

