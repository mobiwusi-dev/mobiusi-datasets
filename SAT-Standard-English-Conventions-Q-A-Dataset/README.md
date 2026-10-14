---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SAT Standard English Conventions Q&A Dataset
---

# SAT Standard English Conventions Q&A Dataset

This dataset presents question-and-answer examples based on standard English conventions found in SAT Reading and Writing preparation materials. Topics include sentence boundaries, punctuation, subject-verb agreement, pronoun reference, modifiers, parallel structure, and verb forms. Records can include source material, a grammar topic, a question type, a canonical answer, its rule basis, boundary-condition analysis, and an explanation of the reasoning process. It supports domain-specific SFT, SAT grammar tutoring, and evaluation of rule-based explanations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| rule_basis | string | A direct quotation or summary of the source rule that supports the canonical answer. |
| answer_text | string | A direct answer to the question, grounded in the source rule text. |
| grammar_topic | string | The primary grammar rule category identified from the question. |
| question_type | string | Classification of the cognitive or response type required by the current Q&A task. |
| reasoning_steps | string | A step-by-step account of how the answer follows from the source material and rule basis. |
| source_material | object | Original input material consisting of rule text, question text, and relevant context. |
| boundary_analysis | string | An explanation of the rule's applicability, limitations, and easily confused exceptions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

