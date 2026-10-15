---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: German Idioms and Fixed Expressions Question Answering Dataset
---

# German Idioms and Fixed Expressions Question Answering Dataset

This dataset is based on web content explaining German idioms, proverbs, collocations, and other fixed expressions. It organizes question-and-answer content around expression categories, literal and idiomatic meanings, usage conditions, and examples in natural contexts. Its structured coverage helps models explain cultural context, semantic distinctions, and usage constraints, supporting German-language QA, learning assistance, and domain-specific instruction tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A complete answer based on the source content that accurately explains the expression and its usage, with examples or cultural context where appropriate. |
| examples | array | Examples showing the expression in natural German contexts, with English translations and contextual notes. |
| question | string | A knowledge question about the expression's literal or idiomatic meaning, usage conditions, or examples. |
| question_type | string | The main type of knowledge addressed by the question. |
| actual_meaning | string | The figurative, conventional, or culturally specific meaning of the expression in real language use. |
| source_webpage | object | Structured content from the original webpage containing the German expression and its explanation. |
| literal_meaning | string | A literal interpretation derived from the usual meanings of the words in the expression. |
| usage_conditions | array | The communicative settings, register, emotional tone, usage limitations, and relevant cultural context for the expression. |
| german_expression | string | A German idiom, proverb, collocation, or fixed expression identified on the webpage. |
| expression_category | string | The category assigned to the German expression. |
| related_expressions | array | German expressions related to the target expression in meaning, structure, usage, or cultural context. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

