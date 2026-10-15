---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Arabic Morphology and Weak Verb Question Answering Dataset
---

# Arabic Morphology and Weak Verb Question Answering Dataset

Built around web text on Arabic morphology, this dataset covers fine-grained topics including roots, verb forms, derived forms, weak verb changes, and noun formation. It pairs questions and answers with source evidence and organizes examples by question type and morphology topic. The data supports specialized question answering, source-grounded response training, and evaluation of models' understanding of Arabic morphological rules.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An accurate response grounded in the source text, which may explain roots, verb forms, derived forms, weak verb changes, or noun formation. |
| question | string | An Arabic morphology question generated from the source text; its content must not go beyond the supplied material. |
| source_text | string | Original Arabic morphology web content or cleaned web text used to generate the question-answer pair. |
| question_type | string | The question category, such as concept explanation, form identification, inflection, form comparison, or rule application. |
| source_evidence | array | Source text excerpts supporting the question and answer, such as short quotations or key terms. |
| knowledge_points | array | Fine-grained Arabic morphology knowledge points extracted from the question-answer pair. |
| morphology_topic | string | The main Arabic morphology topic addressed, such as roots, verb forms, derived forms, weak verbs, or noun formation. |
| is_source_grounded | boolean | Indicates whether the question and answer are fully supported by the source text; set to false when the source does not support them. |
| morphological_analysis | object | A structured summary of relevant roots, verb forms, derived forms, weak verb changes, and noun formation; inapplicable attributes may be omitted. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

