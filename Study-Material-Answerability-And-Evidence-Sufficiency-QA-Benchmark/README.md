---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Study-Material Answerability and Evidence Sufficiency QA Benchmark
---

# Study-Material Answerability and Evidence Sufficiency QA Benchmark

This benchmark contains question-answering examples based on question banks, textbooks, exercises, and other study materials. It covers cases where the material supports an answer, lacks sufficient evidence, or contains conflicting information, with each record providing an answerability judgment, an answer or an empty answer, supporting evidence, and evidence analysis. It can be used to evaluate whether retrieval-augmented question-answering systems find relevant evidence, determine when a question is answerable, and avoid unsupported claims.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise answer supported by the material. Use an empty string when the question cannot be answered reliably from the material. |
| question | string | The question to be answered using the provided study material. |
| answerability | string | Whether the material supports an answer, lacks sufficient evidence, or contains conflicting evidence. |
| study_material | string | The textbook, question bank, exercise, or other source material provided for answering the question. |
| evidence_analysis | string | An explanation of how the cited evidence supports the answer, is insufficient, or conflicts within the material. |
| supporting_evidence | array | Verbatim excerpts from the study material that support the answer or clarify why it cannot be determined. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

