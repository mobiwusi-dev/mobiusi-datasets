---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Power System Relay Protection Practice Q&A Dataset
---

# Power System Relay Protection Practice Q&A Dataset

This dataset contains relay protection practice questions, answers, and explanations for electrical engineering, covering protection principles, fault identification, setting logic, secondary circuits, and substation operations. The web-text records are organized with fields such as knowledge domain, question type, difficulty, key concepts, and reasoning steps for targeted search and filtering. It supports supervised fine-tuning of power engineering question-answering models, knowledge coverage evaluation, and the development of learning support tools.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_text | string | Original answer to the practice question, which may contain an option, judgment, calculation result, or short-answer conclusion. |
| key_concepts | array | Key relay protection concepts, equipment, parameters, or criteria extracted from the question, answer, and explanation. |
| sft_response | string | A complete supervised fine-tuning target response that combines the answer and explanation with professional reasoning. |
| question_text | string | Original text of a power system relay protection practice question. |
| question_type | string | Question format inferred from how the problem is presented and answered. |
| reasoning_steps | array | Ordered steps that organize the explanation into judgments, calculations, references to principles, or derivations of the conclusion. |
| sft_instruction | string | A user question or domain-specific instruction based on the original question and prepared for supervised fine-tuning. |
| difficulty_level | string | Question difficulty based on the breadth of knowledge covered, reasoning complexity, and calculation or analysis requirements. |
| explanation_text | string | Original explanation of the answer, relay protection principles, fault identification criteria, setting logic, or operational procedures. |
| knowledge_domain | string | Primary professional knowledge domain inferred from the question and explanation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

