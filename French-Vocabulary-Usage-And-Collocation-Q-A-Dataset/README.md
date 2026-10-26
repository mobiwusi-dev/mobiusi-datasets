---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: French Vocabulary Usage and Collocation Q&A Dataset
---

# French Vocabulary Usage and Collocation Q&A Dataset

Built around a defined vocabulary list and its supporting examples, this collection covers French word meanings, sense distinctions, common collocations, register, and typical usage contexts. Learner questions are paired with answers grounded in the supplied vocabulary references, making the data suitable for French learning assistants, vocabulary tutoring models, and evaluation of evidence-based responses.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct, learner-friendly response supported by the supplied vocabulary reference material. |
| evidence | array | Specific content from the supplied reference that supports the answer's usage claims. |
| register | string | The expression's stylistic level, such as formal, neutral, informal, or specialized, when supported by the reference. |
| sense_analysis | array | The relevant meanings and distinctions needed to answer the learner's question. |
| learner_question | string | The learner's question about the meaning or use of a French word or expression. |
| typical_contexts | array | Common situations or contexts in which the expression is used. |
| target_expression | string | The French word or expression addressed in the question. |
| reference_material | string | The vocabulary entry and accompanying examples used as the evidence source for the answer. |
| collocation_guidance | array | Natural word combinations and usage patterns relevant to the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

