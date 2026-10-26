---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Bible Cross-Chapter Cross-Reference Multi-Hop QA Dataset
---

# Bible Cross-Chapter Cross-Reference Multi-Hop QA Dataset

This dataset is built from Bible passages with explicitly identified editions and translations, creating multi-hop questions around cross-chapter references, quotations, and parallel passages. Each record includes a question, answer, reasoning steps, textual evidence, cross-reference links, and a hop count to make the answer path traceable. It supports training and evaluating models on biblical text relationships, evidence-based reasoning, and multi-hop question answering.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise answer supported by the supplied Bible passages and their internal relationships. |
| question | string | A question that requires combining information from multiple supplied passages or their explicit relationships. |
| hop_count | integer | The number of distinct inferential transitions needed to connect the source evidence to the answer. |
| bible_edition | string | The explicitly identified Bible translation or edition used for the source passages. |
| reasoning_steps | array | An ordered explanation of how the answer follows from the source passages and cross-reference links. |
| source_passages | array | The Bible passages provided as source material for answering the question. |
| evidence_citations | array | Passage-level textual evidence that directly supports the answer or key reasoning steps. |
| cross_reference_links | array | Explicit links among the supplied passages, including quotations, citations, or parallel passages. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

