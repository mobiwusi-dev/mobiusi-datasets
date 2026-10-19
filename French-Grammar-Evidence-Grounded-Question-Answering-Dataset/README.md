---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: French Grammar Evidence-Grounded Question Answering Dataset
---

# French Grammar Evidence-Grounded Question Answering Dataset

This dataset organizes French grammar rules, conditions of use, examples, and exceptions around specified textbooks or course materials, linking questions and answers to their supporting sources. Its structured records cover source documents, learner questions, answers, grammar analyses, and supporting evidence, making it suitable for training or evaluating models on French grammar questions within a closed corpus. The data supports more accurate, traceable explanations aligned with the designated learning materials.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct, accurate response to the learner's question, grounded in the supplied source. |
| analysis | object | A structured explanation of the grammatical point, including its rule, scope, examples, and source-supported exceptions. |
| evidence | array | Source excerpts and locations that support the answer and its grammar analysis. |
| question | string | A French grammar question to be answered using the supplied source material. |
| source_document | object | Original source material and available document metadata used to answer the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

