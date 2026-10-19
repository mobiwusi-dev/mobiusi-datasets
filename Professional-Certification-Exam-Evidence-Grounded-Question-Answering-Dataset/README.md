---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Professional Certification Exam Evidence-Grounded Question Answering Dataset
---

# Professional Certification Exam Evidence-Grounded Question Answering Dataset

Designed for professional certification exam settings, this dataset pairs exam questions and reference answers with source materials such as textbooks, exam syllabi, regulations, and technical standards, including supporting locations and quotations. It also provides answerability labels and evidence-based explanations for training and evaluating retrieval-augmented generation systems on knowledge retrieval, open-book question answering, and source attribution. Typical uses include exam preparation, intelligent question bank development, and regulation or standards-focused QA.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise answer to the question, supported by the provided source material. |
| question | string | The professional certification exam question to be answered. |
| citations | array | One or more source locations and quotations that directly support the answer. |
| reasoning | string | A brief explanation connecting the cited evidence to the answer, without adding unsupported claims. |
| answerability | boolean | Whether the provided source material contains sufficient evidence to answer the question. |
| source_material | object | The reference material used to ground the answer, such as a textbook, exam syllabus, regulation, or technical standard. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

