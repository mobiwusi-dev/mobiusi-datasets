---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lacquerware Evidence Conflicts and Unanswerable Questions Training Set
---

# Lacquerware Evidence Conflicts and Unanswerable Questions Training Set

This collection contains closed-domain question-answering examples in which lacquerware literature or catalog records disagree, omit relevant information, or do not support an answer. Each example includes a question, source evidence, an answerability status, evidence analysis, and an exemplar response. Designed for domain-specific supervised fine-tuning and evaluation, it trains models to recognize conflicting sources, state evidence limits, and avoid unsupported claims.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | The question to be answered using only the supplied lacquerware sources. |
| evidence_bundle | string | A JSON-encoded collection of source excerpts or catalog records, including source identifiers and relevant metadata. |
| supported_answer | string | The answer justified by the sources, or an explicit statement that the sources do not establish an answer. |
| evidence_analysis | string | A concise analysis of relevant support, disagreements among sources, and limitations in the supplied evidence. |
| exemplar_response | string | A polished model response that describes the evidence boundary and avoids unsupported assertions. |
| answerability_status | string | Indicates whether the supplied evidence supports an answer, contains conflicting claims, or is insufficient to answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

