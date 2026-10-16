---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Korean News and Commentary Discourse Comprehension Dataset
---

# Korean News and Commentary Discourse Comprehension Dataset

This dataset contains news articles, columns, and editorial-style documents in Korean suited to intermediate and advanced learners. JSON annotations capture event structures, arguments and evidence, discourse and causal relations, stance, attribution sources, and document summaries. The collection focuses on cross-sentence meaning and argument organization in formal written Korean, supporting domain-specific SFT as well as training and evaluation for document understanding, information extraction, and discourse analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| event_structure | array | Structured information extracted from the document about events, including triggers, participants, time, and location. |
| source_document | object | The original Korean news article, column, or editorial-style document to be analyzed, together with basic metadata. |
| stance_analysis | object | Analysis of the attitudes and stance strength expressed by the author, media outlet, or other entities toward issues, events, and claims. |
| causal_relations | array | Causes, outcomes, causal trigger expressions, and relation types extracted from the document. |
| document_summary | object | A comprehensive summary of the document's topic, main content, and key viewpoints. |
| argument_structure | array | Annotations of the document's central claims, supporting evidence, reasoning relations, and any counterarguments. |
| attribution_sources | array | Annotations of people, organizations, and other entities quoted, paraphrased, or cited as information sources in the document. |
| discourse_relations | array | Annotations of connections between sentences or paragraphs that capture how formal written text is organized. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

