---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Licensing Agreement Definition and Cross-Reference Evidence Retrieval Benchmark
---

# Licensing Agreement Definition and Cross-Reference Evidence Retrieval Benchmark

This benchmark focuses on questions that require tracing legal support through definitions, cross-references, and incorporated materials in licensing agreements. Records include agreement text, annotated evidence segments and paths, reference answers, and reasoning summaries. It helps evaluate whether retrieval-augmented generation systems can follow contractual relationships to retrieve supporting evidence rather than relying on surface-level keyword matches, and supports legal document retrieval and contract question-answering research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | The benchmark query that requires retrieving legal support from the licensing agreement, including through definitions, cross-references, or incorporated materials. |
| gold_answer | string | The reference answer to the question, supported by the annotated evidence and retrieval paths. |
| agreement_text | string | The source licensing agreement text to search, including any available text of materials incorporated by reference. |
| evidence_paths | array | The annotated chains of contractual relationships that connect the question or an initial clause to supporting evidence. |
| evidence_segments | array | The annotated text spans that provide relevant legal support for answering the question. |
| reasoning_summary | string | A concise explanation of how the linked contractual provisions establish the gold answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

