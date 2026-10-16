---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Digital Humanities Textbook Historical Source Contextual Question Answering Dataset
---

# Digital Humanities Textbook Historical Source Contextual Question Answering Dataset

This dataset contains humanities questions grounded in excerpts, annotations, background notes, and analyses from digital textbooks in history, literature, and the social sciences. Topics include source attribution, historical context, central arguments, relationships among figures, and evidence interpretation. Records provide reference answers and supporting evidence details, making the collection useful for domain-specific fine-tuning, knowledge-based QA evaluation, and research on long-tail questions that require contextual grounding.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A complete answer based on the original textbook material that directly addresses the question and respects the source context. |
| question | string | A humanities question based on textbook source material and its context, requiring an answer informed by subject-matter knowledge. |
| core_claims | array | The main arguments or conclusions distilled from the textbook material and answer. |
| key_entities | array | Important people, works, organizations, places, events, or concepts mentioned in the question and answer. |
| evidence_spans | array | Original text excerpts that support the answer, with their roles in the reasoning. |
| question_focus | string | The main aspect addressed by the question, such as source attribution, historical context, central arguments, relationships among figures, concept interpretation, or evidence reasoning. |
| source_material | object | Original sources, annotations, background notes, and analyses from digital textbook pages in history, literature, or the social sciences. |
| answer_confidence | number | A confidence score from 0 to 1 based on evidence sufficiency, context completeness, and clarity of source attribution. |
| historical_period | string | The historical period, literary period, or social and intellectual context relevant to the question and answer. |
| evidence_explanation | string | Explains which source content, annotations, or textbook analysis supports the answer and how the evidence supports the conclusion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

