---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SAT Rhetorical Analysis, Synthesis, and Cohesion QA Dataset
---

# SAT Rhetorical Analysis, Synthesis, and Cohesion QA Dataset

This dataset brings together text-based question-and-answer samples from SAT preparation webpages and curated materials, covering central ideas, rhetorical purpose, information synthesis, logical transitions, and text organization. Questions are grounded in source passages and may include normalized answers, reasoning, and supporting evidence spans for traceable responses. It supports focused SAT tutoring, reading comprehension practice, and model evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question_type | string | SAT rhetorical analysis or text organization question type inferred from the question's intent. |
| evidence_spans | array | Source text excerpts that support the answer and reasoning, with notes on their function. |
| answer_rationale | string | Explanation of how the answer follows from textual evidence, including relevant rhetorical or cohesive functions. |
| logical_relation | object | Summary of logical relationships between sentences or paragraphs and the transitions that signal them. |
| rhetorical_focus | array | Rhetorical strategies, information organization, or reading skills identified from the source text and question. |
| source_qa_record | object | Original passage excerpts, questions, reference answers, and source information from SAT preparation webpages or curated files. |
| normalized_answer | string | A concise, complete answer edited to preserve the original meaning and support model training and evaluation. |
| document_structure | object | Analysis of how the passage or relevant paragraphs are organized, how information develops, and what structural functions the parts serve. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

