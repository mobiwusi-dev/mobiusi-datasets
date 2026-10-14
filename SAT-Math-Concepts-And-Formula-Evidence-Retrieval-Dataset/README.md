---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SAT Math Concepts and Formula Evidence Retrieval Dataset
---

# SAT Math Concepts and Formula Evidence Retrieval Dataset

Designed for SAT math questions, this dataset pairs original question text and structured conditions with relevant concept definitions, formulas or theorems, applicability conditions, solution links, and source materials. Its JSON records include consolidated retrieval text and an evidence quality score ranging from 0 to 1, supporting workflows that retrieve reliable mathematical grounds for each question. Typical uses include RAG knowledge retrieval, evidence-backed explanations, and retrieval system development and evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question_text | string | The complete original SAT math question, including its prompt, requested task, and mathematical expressions. |
| retrieval_text | string | Evidence text combining question conditions, concepts, formulas or theorems, applicability conditions, and solution links for RAG retrieval and generation. |
| evidence_quality | number | A composite score from 0 to 1 assessing mathematical evidence accuracy, source traceability, and relevance to solving the question. |
| source_knowledge | string | Original materials used to extract or verify mathematical concepts, definitions, formulas, theorems, and their sources. May include textbooks, official resources, or curated knowledge excerpts. |
| solution_relation | object | Annotations describing how the question conditions and mathematical evidence correspond to the solution process. |
| knowledge_evidence | object | Concept definitions, formulas or theorems, applicability conditions, and reliable source evidence relevant to solving the question. |
| structured_conditions | object | Structured information extracted from the question text, such as question type, given conditions, objective, and answer choices. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

