---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SAT Answer Choice Support and Refutation Evidence Dataset
---

# SAT Answer Choice Support and Refutation Evidence Dataset

This dataset contains SAT Reading and Writing questions, answer choices, relevant passage excerpts, and evidence annotations that support the correct choice or refute distractors. Its structured JSON records help systems retrieve and cite the textual basis for distinguishing among choices, reducing reliance on superficial lexical matches. It is suited to SAT preparation tools, educational question-answering systems, and retrieval-augmented generation research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_key | object | The answer inferred from evidence supporting the correct choice, together with its rationale. |
| source_record | object | The original text of an individual question, its answer choices, and human-labeled evidence. |
| evidence_index | array | An index of the original evidence annotations, organized to help retrieval-augmented systems locate and cite relevant evidence. |
| coverage_report | object | A statistical summary of evidence coverage for the answer choices, including supporting and refuting evidence. |
| retrieval_query | string | A retrieval query generated from the question, passage, and answer choice discrimination requirements. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

