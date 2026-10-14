---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SAT Standard English Conventions Rule Evidence Dataset
---

# SAT Standard English Conventions Rule Evidence Dataset

This dataset covers SAT grammar and rhetorical editing questions, passages to revise, related rule entries and examples, and links between rules and answers, organized as JSON records. It focuses on common language issues such as punctuation, syntax, cohesion, and expression, and supports retrieval of applicable rules and evidence for answer decisions. Use it to build SAT tutoring, rule retrieval, and answer explanation systems that provide grounded explanations.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question_type | string | The primary skill category inferred from the question content. |
| source_record | object | The original JSON record containing the question and its associated rule data. |
| evidence_spans | array | Evidence excerpts from the prompt, passage to revise, answer choices, or rule descriptions that support the answer and rule decision. |
| issue_categories | array | One or more language issue categories identified from the question and passage to revise. |
| rule_answer_link | object | A structured summary of the relationship between the correct answer and the applicable rule. |
| answer_explanation | string | A complete explanation based on the applicable rules and evidence spans, describing why the correct choice works and what is wrong with the other choices. |
| applicable_rule_keys | array | The set of rule keys retrieved and determined to apply based on the question, answer choices, and passage issues. |
| annotation_confidence | number | A numeric confidence score for the overall consistency of the question type, applicable rules, evidence spans, and answer explanation, ranging from 0 to 1. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

