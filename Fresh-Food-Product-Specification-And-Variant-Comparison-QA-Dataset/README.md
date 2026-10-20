---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Fresh Food Product Specification and Variant Comparison QA Dataset
---

# Fresh Food Product Specification and Variant Comparison QA Dataset

This dataset provides retrieval and comparison questions about same-brand or same-series products in grocery and fresh food delivery catalogs, covering differences in size, flavor, and packaging. Each example links relevant catalog records with an extracted comparison target, attribute-level findings, an answer, and supporting evidence, helping models identify the correct variant and respond from catalog information. It is suited to training and evaluating retrieval-augmented generation, product catalog question answering, and shopping assistants.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | The final response, grounded in the relevant catalog records and comparison findings. |
| evidence | array | Excerpts from catalog records that jointly support the answer. |
| question | string | The original question requesting retrieval, identification, or comparison of product variants. |
| catalog_records | array | The original product catalog listings available as evidence for answering the question. |
| comparison_target | object | The product identity and variant criteria extracted from the question to guide catalog retrieval and comparison. |
| comparison_findings | array | Attribute-by-attribute comparison findings derived from the selected catalog listings. |
| selected_catalog_codes | array | References identifying the catalog records selected as relevant to the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

