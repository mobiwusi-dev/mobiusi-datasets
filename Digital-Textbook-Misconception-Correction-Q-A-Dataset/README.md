---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Digital Textbook Misconception Correction Q&A Dataset
---

# Digital Textbook Misconception Correction Q&A Dataset

This dataset presents question-and-answer examples about commonly confused concepts, incorrect claims, counterexamples, misconception alerts, and knowledge boundaries in digital textbooks. Records include source material, normalized questions, corrective answers, misconception types, key concepts, correction points, and answer quality scores. It supports training models to clarify specialized knowledge with textbook-based explanations, distinguish long-tail concepts, and explain the limits of a claim.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A complete user-facing answer that identifies the error, states the correct interpretation, and explains it with textbook evidence, a counterexample, or applicable boundaries. |
| question | string | A concept-disambiguation question rewritten from an incorrect claim in a form suitable for users. |
| key_concept | string | The concept, term, or knowledge point that the Q&A item is intended to clarify. |
| source_record | object | Original misconception-correction content from digital textbooks or human curation, provided as input for question-and-answer generation and annotation. |
| answer_quality | number | An overall score from 0 to 1 for the corrective answer, based on accuracy, consistency with the textbook, adequacy of boundary explanations, and clarity. |
| correction_points | array | Key points extracted from the corrective explanation and ordered to support understanding. |
| misconception_type | string | A category for the incorrect claim, such as concept confusion, omitted conditions, reversed causality, overgeneralization, or overlooking counterexamples. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

