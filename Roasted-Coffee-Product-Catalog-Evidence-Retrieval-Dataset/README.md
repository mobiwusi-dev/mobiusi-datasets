---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Roasted Coffee Product Catalog Evidence Retrieval Dataset
---

# Roasted Coffee Product Catalog Evidence Retrieval Dataset

This dataset contains roasted coffee catalog entries, source excerpts with product information, and evidence annotations for product attribute questions, covering catalog details such as product names, roast levels, package sizes, and flavor descriptions. It also includes retrieval queries, normalized product attributes, evidence spans, verification results, and answerability labels for building and evaluating RAG systems that retrieve supporting catalog evidence. The data helps connect product attribute answers to specific source material and supports coffee catalog question answering and retrieval quality evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| catalog_entry | object | The original catalog details for the roasted coffee product. |
| evidence_spans | array | Evidence spans aligned to the source excerpt and derived from the evidence annotation. |
| source_excerpt | string | The original source text containing product information that may support an answer. |
| retrieval_query | string | A normalized retrieval query derived from the product details and attribute question. |
| evidence_verified | boolean | Whether the annotated evidence quote can be matched to the source excerpt. |
| attribute_question | string | The question about a product attribute that the evidence should support. |
| answerability_label | boolean | Whether the source excerpt provides sufficient evidence to answer the attribute question. |
| evidence_annotation | object | The original annotation identifying the attribute and relevant supporting evidence. |
| normalized_product_attributes | object | Product attributes standardized from the original catalog entry for consistent retrieval and evaluation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

