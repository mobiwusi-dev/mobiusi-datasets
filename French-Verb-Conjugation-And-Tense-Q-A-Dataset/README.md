---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: French Verb Conjugation and Tense Q&A Dataset
---

# French Verb Conjugation and Tense Q&A Dataset

This dataset provides question-and-answer content on common French verb conjugations, tense formation, differences in meaning, and irregular forms. Answers are grounded in an approved verb list and grammar reference materials, helping models connect specific verb forms to applicable rules. It is suited to French grammar QA, language-learning support, and domain-specific supervised fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | The direct answer to the French verb knowledge question. |
| question | string | The original question about French verb conjugation, tense formation, or usage. |
| relevant_verb | string | The infinitive relevant to the answer, selected from the approved verb list when applicable. |
| tense_or_mood | string | The tense or mood addressed by the answer, when applicable. |
| conjugated_form | string | The French conjugated form relevant to the answer, when applicable. |
| rule_explanation | string | A concise explanation connecting the answer to the applicable conjugation rule or grammar reference. |
| grammar_reference | string | Reference material that provides grammatical rules and supporting evidence for the answer. |
| approved_verb_list | string | The restricted list of verbs that may be used when answering the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

