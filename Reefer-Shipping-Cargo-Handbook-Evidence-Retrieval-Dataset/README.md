---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Reefer Shipping Cargo Handbook Evidence Retrieval Dataset
---

# Reefer Shipping Cargo Handbook Evidence Retrieval Dataset

This dataset pairs user queries about reefer shipping requirements with relevant evidence passages from cargo transportation handbooks, covering temperature settings, ventilation, loading, and other transport conditions. Records include query text, cargo names, requirement categories, supporting answers, and source references to enable traceable handbook retrieval. It supports training and evaluation of retrieval-augmented generation systems, helping improve evidence matching and verifiability in shipping requirement answers.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| cargo_name | string | The cargo name identified from the query and handbook evidence. |
| query_text | string | The original user query about transportation requirements for reefer shipping cargo. |
| answer_text | string | The transportation requirement answer to the query, grounded in the handbook evidence. |
| handbook_passage | string | The original cargo transportation handbook passage relevant to the query. |
| source_reference | string | Source information for locating the evidence passage, such as the handbook name, chapter, page number, or another reference. |
| requirement_category | string | The category of transport requirement addressed by the evidence, such as temperature settings, ventilation, loading, or other transport conditions. |
| evidence_supports_query | boolean | Indicates whether the handbook evidence passage supports the answer given to the query. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

