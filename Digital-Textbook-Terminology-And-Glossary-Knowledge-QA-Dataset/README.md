---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Digital Textbook Terminology and Glossary Knowledge QA Dataset
---

# Digital Textbook Terminology and Glossary Knowledge QA Dataset

This dataset draws on terminology lists, sidebar definitions, concept cards, and chapter explanations from digital textbook web pages. It covers question answering about term definitions, distinctions between terms, hierarchical relationships, and discipline-specific contexts, with records that can include source material, answers, related terms, and supporting excerpts. It supports specialized vocabulary learning, domain-focused question answering, and textbook knowledge services.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An accurate and complete response grounded in the textbook material and appropriate to the relevant disciplinary context. |
| keywords | array | Terms, concepts, disciplines, and relationships extracted from the question-answer content. |
| question | string | A user question about a term definition, a distinction between terms, a hierarchical relationship, or a discipline-specific context. |
| is_answerable | boolean | Indicates whether the source textbook material supports a sufficiently clear and complete answer to the question. |
| question_type | string | The knowledge question category assigned to this question-answer sample. |
| related_terms | array | A list of other terms connected to the core term through definitions, distinctions, or hierarchical relationships. |
| relation_type | string | The semantic or hierarchical relationship between the core term and related terms; use no explicit relationship when none applies. |
| evidence_quote | string | A quotation or key explanatory passage from the textbook that supports the answer. |
| source_material | object | Terminology and its original context from a digital textbook web page or textbook page; provided as an independent input source for generating questions and answers. |
| difficulty_level | string | The difficulty level assigned according to the term's specialization, relationship complexity, and dependence on context. |
| discipline_context | string | An explanation of the term's meaning and usage boundaries within a specific discipline, chapter topic, or professional setting. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

