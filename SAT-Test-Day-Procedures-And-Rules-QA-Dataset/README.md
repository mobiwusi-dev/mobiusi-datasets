---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SAT Test Day Procedures and Rules QA Dataset
---

# SAT Test Day Procedures and Rules QA Dataset

This dataset provides web-text question-answer pairs about SAT test day procedures and testing rules, including check-in, identity verification, device preparation, breaks, test room conduct, late arrival, and practical reminders. Records include source webpage text, candidate questions, reference answers, topic labels, and annotations for procedures and rules, supporting models that answer SAT test day questions based on source material. Use it for domain instruction tuning, rule retrieval, and QA system evaluation to help candidates understand test day requirements.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| topic | string | The SAT test day topic covered by the question-answer pair. |
| answer | string | An accurate, complete, candidate-focused answer based on the source webpage text. |
| question | string | A candidate's question about SAT test day procedures or rules. |
| rule_type | string | The type of rule or information addressed by the question-answer pair. |
| conditions | object | The intended audience, prerequisites, and limitations for the rule. |
| key_reminders | array | Important points candidates should pay particular attention to. |
| procedure_steps | array | Test day procedure steps and execution requirements extracted from the webpage text. |
| applicable_stage | array | The test day stage or stages to which the procedure or rule applies. |
| evidence_excerpt | string | A relevant excerpt from the source webpage or a summary of the supporting evidence. |
| exception_handling | object | Guidance for late arrival, device issues, or other exceptional situations. |
| source_webpage_text | string | Original SAT test day webpage text used to create the question-answer pair. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

