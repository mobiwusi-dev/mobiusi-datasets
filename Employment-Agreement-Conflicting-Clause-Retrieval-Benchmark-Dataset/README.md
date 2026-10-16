---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Employment Agreement Conflicting Clause Retrieval Benchmark Dataset
---

# Employment Agreement Conflicting Clause Retrieval Benchmark Dataset

This benchmark covers cases involving conflicting language, overlapping scope, or unclear precedence within an employment agreement, between a main agreement and its attachments, or across document versions. Each case includes contract content, version information, and a retrieval question, along with annotations for conflict assessment and evidence fragments that should be retrieved together. It supports evaluation of whether legal RAG systems retrieve the full conflict context rather than returning only a single similar clause.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_source | object | The original input object containing contract document content, version information, and the retrieval question. |
| retrieval_target | object | The target requirements used to evaluate whether a retrieval system returns the complete conflict context. |
| evaluation_labels | object | Standard annotations describing candidate evidence relevance, necessity, and role in the conflict. |
| evidence_fragments | array | Related contract clauses or contextual fragments that should be jointly covered by the retrieval results. |
| conflict_assessment | object | The conflict type, scope, and precedence assessment derived from the source contract documents and retrieval question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

