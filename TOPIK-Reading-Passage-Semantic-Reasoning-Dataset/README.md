---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: TOPIK Reading Passage Semantic Reasoning Dataset
---

# TOPIK Reading Passage Semantic Reasoning Dataset

Designed for TOPIK Korean reading exam scenarios, this dataset provides structured Korean passages, questions, answer choices, correct answers, semantic judgments, explanations, and supporting evidence sentences. It covers main-idea identification, information retrieval, contextual word meaning, inter-sentence logic, and implied intent, supporting the development and improvement of Korean document understanding models. Its JSON input-output structure is suitable for domain-specific supervised fine-tuning, model evaluation, and answer traceability.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| explanation | string | Explains how the correct answer is derived from the passage, context, and relationships between sentences. |
| input_record | object | Contains the original Korean reading passage, question, answer choices, question type, and other information to be analyzed. |
| correct_option | string | The option number or label identified as correct through semantic reasoning about the passage. |
| semantic_judgment | string | A consolidated judgment of the semantic relationship between the passage, question, and correct option. |
| evidence_sentences | array | A list of original passage sentences or key statements that support the correct answer. |
| correct_answer_text | string | The full answer text corresponding to the correct option. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

