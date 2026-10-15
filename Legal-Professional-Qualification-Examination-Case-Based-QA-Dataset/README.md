---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Legal Professional Qualification Examination Case-Based QA Dataset
---

# Legal Professional Qualification Examination Case-Based QA Dataset

This dataset brings together case questions, statutory application questions, answer options, answers, and explanations from legal qualification exam and legal studies practice pages. It covers substantive law, procedural rules, and integrated case analysis, while linking case facts and legal elements to applicable rules, reasoning, and conclusions. It is designed for legal-domain question answering, case-reasoning evaluation, and specialized legal knowledge retrieval.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| legal_rules | array | Legal provisions, constituent elements, conditions for application, and supporting legal authorities extracted from the question and explanation. |
| legal_domain | string | The primary branch or specialized area of law inferred from the case facts, question, and explanation. |
| question_type | string | The case question category inferred from its content, such as substantive law application, procedural law judgment, statutory interpretation, or integrated analysis. |
| source_record | object | The original case question-and-answer content collected from a legal exam or law practice page, serving as the independent source for this record. |
| facts_elements | array | Facts, conduct elements, relationships between parties, and outcome elements extracted from the case that directly affect the legal judgment. |
| reasoning_chain | array | The case reasoning organized by relevant facts, legal rules, rule application, and intermediate conclusions, preserving the links between facts and conclusions. |
| answer_conclusion | string | The final legal judgment or correct answer choice derived from the facts, legal rules, and reasoning chain. |
| procedural_issues | array | Procedural law issues identified in the case, such as jurisdiction, standing, deadlines, evidence, procedural steps, or available remedies. |
| boundary_conditions | array | Exceptions, limitations, counterexamples, and easily confused scenarios that may affect the scope or outcome of applying a legal rule. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

