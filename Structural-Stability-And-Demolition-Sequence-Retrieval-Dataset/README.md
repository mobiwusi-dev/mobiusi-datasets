---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Structural Stability and Demolition Sequence Retrieval Dataset
---

# Structural Stability and Demolition Sequence Retrieval Dataset

This dataset is based on web text related to demolition safety, with a focus on structural stability, temporary support, load-bearing components, and demolition sequence. Each record organizes a retrieval query, its intent, and supporting source passages; demolition steps, structural risks, and stability measures are included when available in the source. It supports the development and evaluation of RAG retrieval systems for demolition safety, helping locate information about work sequencing and structural hazards.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| query | string | A question or search query about structural stability, temporary support, load-bearing components, or demolition sequence. |
| query_intent | string | The primary information need expressed by the query. |
| answer_summary | string | A concise synthesis of the answer supported by the retrieved evidence. |
| source_document | object | The original webpage content used as the input source for this record. |
| structural_risks | array | Structural instability or collapse risks identified in relation to the query. |
| evidence_passages | array | Source passages selected as evidence for answering the retrieval query. |
| stability_measures | array | Temporary support and other measures that maintain stability during demolition. |
| demolition_sequence | array | Ordered demolition actions and their dependencies, when sequence information is present in the source. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

