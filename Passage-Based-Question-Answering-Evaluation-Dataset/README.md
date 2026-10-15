---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Passage-Based Question Answering Evaluation Dataset
---

# Passage-Based Question Answering Evaluation Dataset

This dataset contains web-text questions from digital question banks that require answers grounded in short passages, case studies, chart descriptions, or reference materials. It includes raw question records, normalized reference answers, annotated answer evidence, and semantic annotations, supporting evaluation of contextual evidence use, reference resolution, and answer grounding. It is suitable for question answering benchmarks, reading comprehension analysis, and the evaluation and improvement of education-focused models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reference_answer | string | A cleaned and normalized version of the original answer, provided as a reference for evaluating model responses. |
| raw_question_record | object | The unnormalized source record for a passage-based question, including the supplied material, question, options, and original answer where available. |
| evidence_annotations | array | Identifies material spans that support the reference answer, their character positions, and their evidential roles. |
| semantic_annotations | object | Annotations derived from the material, question, and reference answer, covering question type, reasoning requirements, reference relations, and answer support. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

