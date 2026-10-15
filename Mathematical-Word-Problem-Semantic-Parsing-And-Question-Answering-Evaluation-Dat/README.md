---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mathematical Word Problem Semantic Parsing and Question Answering Evaluation Dataset
---

# Mathematical Word Problem Semantic Parsing and Question Answering Evaluation Dataset

This dataset covers mathematical word problems, their stated conditions, question targets, and reference answers, with structured details for quantities, units, relationships, operations, and implicit conditions. It includes normalized questions, question types, and structured answer targets to help assess how well models interpret natural-language problems and turn them into answerable questions. It is suitable for developing mathematical QA systems, studying semantic parsing, and evaluating models in the domain.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| operation | string | Identifies the primary mathematical operation inferred from the problem, such as addition, subtraction, multiplication, division, or comparison. |
| relations | array | Records quantity, comparison, or operational relationships parsed between entities in the problem. |
| quantities | array | Lists quantities, units, entities, and their semantic roles as identified from the problem conditions. |
| answer_target | object | Parses the reference answer into a structured target that can be calculated or validated. |
| question_type | string | Categorizes the question by its goal, such as finding a sum, difference, multiple, comparison, or remaining quantity. |
| problem_record | object | Contains the original text of the mathematical word problem, its question, and the reference answer. |
| unit_constraints | array | Specifies unit-consistency requirements for calculating or comparing quantities and expressing the answer. |
| implicit_conditions | array | Captures conditions inferred from common knowledge, grammar, or problem structure that are not fully stated but are relevant to solving the problem. |
| normalized_question | string | Rephrases the original question to make its meaning explicit, resolve references, and support calculation or direct answering. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

