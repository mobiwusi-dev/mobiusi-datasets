---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Negation and Exception Question-Answering Challenge Set
---

# Negation and Exception Question-Answering Challenge Set

This dataset contains text-based question-answer samples collected from online question banks, covering negation, exceptions, scope, and conditional constraints such as “incorrect,” “does not belong to,” “except,” and “main reason.” It includes normalized questions, annotations of limiting expressions, option-level semantic analysis, gold answers, and diagnostic labels for semantic failure modes. Use it to evaluate question-bank QA, semantic understanding, and model robustness in exam settings.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_record | object | Original text collected from a question-bank webpage, including structured question, option, and answer content. |
| gold_answer | object | A normalized annotation of the correct answer and its semantic basis. |
| cue_annotations | array | Negation, exception, scope, and conditional cues in the question that affect answer selection. |
| option_analysis | array | An assessment of how each option matches the question constraints and the requirements for the correct answer. |
| question_task_type | string | The primary negation, exception, scope, or conditional constraint assessed by the question. |
| diagnostic_annotation | object | Labels for evaluating whether a model correctly handles negation, scope, and conditional constraints in a question. |
| normalized_question_text | string | Question text with formatting noise cleaned up without changing its meaning. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

