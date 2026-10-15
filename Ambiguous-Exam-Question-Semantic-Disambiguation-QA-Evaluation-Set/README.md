---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Ambiguous Exam Question Semantic Disambiguation QA Evaluation Set
---

# Ambiguous Exam Question Semantic Disambiguation QA Evaluation Set

This evaluation set contains web text from digital question banks, focusing on issues that can affect question interpretation, including unclear references, polysemous terms, missing conditions, omitted expressions, and distracting wording. Each record is organized around question interpretation, ambiguity identification, answerability judgment, a reference answer, and supporting rationale, enabling systematic evaluation of how models handle semantic ambiguity in exam questions. It is suitable for digital question bank quality analysis, educational QA evaluation, and semantic understanding research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_basis | string | An explanation of how the reference answer follows from the question conditions, interpretation, and required assumptions, identifying any ambiguity that could affect the conclusion. |
| webpage_text | string | Original webpage text containing a digital exam question and its context, preserving references, terminology, conditions, omissions, and distracting wording. |
| answerability | boolean | Whether the information provided in the question alone supports a unique, clear, and verifiable answer; true indicates that it does, and false indicates that it does not. |
| ambiguity_types | array | All major semantic ambiguity types present in the question, selected from predefined categories. |
| reference_answer | string | An answer, answer range, or conclusion that cannot be determined, based on the original question and any explicitly stated assumptions; key intermediate results may be included. |
| ambiguity_evidence | array | Words, phrases, sentences, or contextual clues quoted or summarized from the question to support the ambiguity judgment. |
| answerability_reason | string | An explanation of why the question is answerable or unanswerable, focusing on information sufficiency, answer uniqueness, and the effect of ambiguity on solving it. |
| required_assumptions | array | Prerequisites, definitions, values, or contextual information that must be added to provide a definite interpretation or answer; enter no additional assumptions if none are needed. |
| clarification_question | string | A question that would supply missing conditions or resolve multiple interpretations when ambiguity affects answering; enter no clarification needed when the question is clear. |
| question_interpretation | string | A description of the intended subject, question objective, and calculation or reasoning relationships, including how ambiguous content is interpreted. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

