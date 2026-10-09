---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Arabic Pragmatics and Register Retrieval Dataset
---

# Arabic Pragmatics and Register Retrieval Dataset

This dataset is compiled from Arabic-learning web pages and includes contextual questions, relevant explanatory passages, and the Arabic words, phrases, or sentence patterns they discuss. Records describe communicative intent, politeness strategies, register, Arabic variety, and usage context, while retaining page titles and source URLs for traceability. It supports Arabic knowledge retrieval, retrieval-augmented generation, language-learning question answering, and pragmatic analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| register | string | The register in which the expression is used, such as formal, informal, written, or spoken. |
| source_url | string | The URL extracted from the source web page for tracing the supporting information. |
| source_html | string | Original HTML content from an Arabic-learning web page, serving as the source for knowledge extraction and passage matching. |
| source_title | string | The title extracted from the source web page. |
| usage_context | string | A description of the situations, interlocutors, and contextual conditions in which the expression is appropriate. |
| arabic_variety | string | The Arabic variety associated with or applicable to the expression, such as Modern Standard Arabic or a regional dialect; may be blank when undetermined. |
| arabic_expression | string | The Arabic word, phrase, or sentence pattern discussed in the supporting passage. |
| supporting_passage | string | A passage extracted from the web page that explains or answers the contextual question. |
| contextual_question | string | A question about the intent, politeness, register, or usage context of an Arabic expression. |
| politeness_strategy | string | The politeness level, strategy, or approach to managing interpersonal relations reflected in the expression. |
| communicative_intent | string | The primary intent or communicative function conveyed by the expression in context. |
| question_passage_relation | string | An explanation of how the passage addresses the contextual question and which pragmatic cues can support retrieval matching. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

