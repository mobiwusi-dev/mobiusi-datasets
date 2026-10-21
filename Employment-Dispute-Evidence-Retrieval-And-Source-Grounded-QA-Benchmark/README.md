---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Employment Dispute Evidence Retrieval and Source-Grounded QA Benchmark
---

# Employment Dispute Evidence Retrieval and Source-Grounded QA Benchmark

This benchmark contains question-answering examples about employment dispute case facts, agreements, rules, and decisions. Models must retrieve relevant support from the supplied materials and answer with clear distinctions between established facts and unconfirmed details. Each example captures the question, source materials, grounded answer, answerability status, evidence references, and unconfirmed points for evaluating and improving retrieval-augmented legal systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An answer based on the supplied materials that distinguishes established facts from uncertainty where relevant. |
| evidence | array | Specific source passages and their relationship to the answer. |
| question | string | The employment dispute question to be answered using the provided source materials. |
| source_materials | array | The case facts, agreements, rules, or decisions supplied as evidence for answering the question. |
| unconfirmed_points | array | Claims or details relevant to the question that the supplied materials do not establish or allow the answer to verify. |
| answerability_status | string | The extent to which the supplied materials establish an answer to the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

