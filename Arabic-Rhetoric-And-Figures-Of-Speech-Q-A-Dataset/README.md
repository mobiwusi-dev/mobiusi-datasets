---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Arabic Rhetoric and Figures of Speech Q&A Dataset
---

# Arabic Rhetoric and Figures of Speech Q&A Dataset

This dataset uses Arabic rhetoric teaching webpages and related texts as its knowledge boundary, with questions and reference answers covering concepts such as simile, metaphor, metonymy, pun, restriction, and emphasis. Its fields support term identification, definition, explanation of rhetorical function, and analysis of examples. The data is designed for supervised fine-tuning, Arabic learning assistants, and closed-domain evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A reference answer grounded in the teaching material, intended for supervised fine-tuning in specialized Arabic learning. |
| question | string | A question about Arabic rhetoric that should be answered using the teaching material. |
| rhetorical_term | string | The core Arabic rhetorical term addressed in the question or answer, such as simile, metaphor, metonymy, pun, restriction, or emphasis. |
| source_material | string | Arabic rhetoric teaching webpages or related text used as the knowledge boundary for the question and answer. |
| example_analysis | string | An analysis of an Arabic example from the teaching material, covering device identification, structure, and semantic effect. |
| rhetorical_function | string | An explanation of the rhetorical device's expressive effect, pragmatic function, or emphasis in context. |
| rhetorical_definition | string | An explanation of the concept, structure, or linguistic meaning of the identified rhetorical term. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

