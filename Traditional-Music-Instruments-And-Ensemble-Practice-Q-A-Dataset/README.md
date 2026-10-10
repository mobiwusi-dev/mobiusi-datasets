---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Traditional Music Instruments and Ensemble Practice Q&A Dataset
---

# Traditional Music Instruments and Ensemble Practice Q&A Dataset

This dataset presents questions, answers, and related source materials about instrument functions, ensemble configurations, tunes and repertoire, and performance occasions in traditional performance music. Answers are linked to passages or source identifiers, with a focus on musical practice rather than general instrument descriptions. It is suited to closed-domain question answering, evidence-grounding training, and fine-tuning models for traditional performing arts.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise, expert response to the question based on the supplied source material. |
| evidence | array | One or more supporting excerpts from the supplied source material, with source locations. |
| question | string | The original question about a traditional music instrument or performance practice. |
| knowledge_focus | string | The main category of musical performance practice addressed by the question. |
| source_material | object | The source materials used to answer the question, together with their source information. |
| instrument_names | array | Names of traditional instruments mentioned in the question or answer. |
| tune_or_repertoire | string | Information about related tunes, repertoire, or tune types; may be empty when not applicable. |
| performance_function | string | The function or role of an instrument in performance or an ensemble, including how instruments coordinate; may be empty when not applicable. |
| performance_occasion | string | The related performance occasion, ceremony, or social context; may be empty when not applicable. |
| ensemble_configuration | string | The instrument combination, ensemble makeup, or part arrangement; may be empty when not applicable. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

