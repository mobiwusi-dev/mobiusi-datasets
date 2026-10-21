---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Painting Heritage Provenance Chain Multi-Hop QA Dataset
---

# Painting Heritage Provenance Chain Multi-Hop QA Dataset

This dataset focuses on paintings' historical owners, collecting institutions, transfer events, and related documentary records. It contains questions that require linking multiple provenance nodes and dates, along with answers, provenance chains, reasoning steps, and evidence links. The text-based data supports training and evaluating provenance tracing and evidence-based reasoning in painting heritage research, without requiring image input.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_text | string | Concise answer derived from the source materials and directly addressing the question. |
| question_text | string | Question to answer by tracing the painting's provenance across multiple source nodes and points in time. |
| evidence_links | array | Specific documentary evidence supporting the answer and inferences made along the provenance chain. |
| reasoning_steps | array | Ordered explanation showing how the answer follows from linking provenance nodes, dates, and source evidence. |
| provenance_chain | array | Ordered sequence of owners, collections, or transfer events used to establish the answer. |
| source_materials | object | Original source packet containing painting details, provenance records, ownership or transfer events, and documentary references. Preserve the source wording and references when available. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

