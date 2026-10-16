---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Korean Pragmatics and Cultural Context Evidence Retrieval Dataset
---

# Korean Pragmatics and Cultural Context Evidence Retrieval Dataset

This collection links Korean learners' questions to cultural education webpage content across scenarios such as forms of address, requests and refusals, dining etiquette, workplace communication, age relations, and social expressions. Records include pragmatic context analysis, target Korean expressions, evidence claims and supporting webpage excerpts, along with source references and retrieval tags. The data supports Korean learning assistants that provide context-aware advice grounded in traceable sources.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| learner_query | string | The learner's original question about Korean pragmatics, etiquette, or a cultural situation. |
| evidence_claim | string | A cultural or language-use conclusion derived from the webpage and able to directly support pragmatic advice. |
| evidence_spans | array | Source text excerpts that support the evidence claim, including their locations and roles. |
| retrieval_tags | array | Tags for retrieving the record by pragmatic topic, cultural concept, and communication conditions. |
| source_webpage | object | A snapshot of the cultural education webpage providing contextual evidence, together with basic metadata. |
| confidence_score | number | A score from 0 to 1 measuring the association among the question, webpage evidence, and inferred conclusion. |
| pragmatic_context | object | The communicative relationships, setting, and politeness conditions extracted from the question and webpage evidence. |
| scenario_category | string | The primary pragmatic or cultural learning scenario inferred from the learner's question. |
| evidence_reference | object | Citation details for tracing and displaying the webpage evidence source. |
| target_expressions | array | Korean forms of address, sentence patterns, words, or expressions relevant to the question and intended for learning or comparison. |
| source_supports_advice | boolean | Indicates whether the webpage evidence is sufficient to directly support pragmatic advice for the learner's question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

