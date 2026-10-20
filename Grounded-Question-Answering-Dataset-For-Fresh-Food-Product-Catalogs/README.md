---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Grounded Question Answering Dataset for Fresh Food Product Catalogs
---

# Grounded Question Answering Dataset for Fresh Food Product Catalogs

This dataset contains question-answering samples based on product catalogs for fresh food and grocery delivery. It covers catalog details such as product names, brands, sizes, prices, and descriptions, linking each question and answer to supporting catalog evidence. Use it to train and evaluate retrieval-augmented generation systems that answer product questions from retrieved records and provide traceable support.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| user_question | string | The question asked about the product or its catalog information. |
| grounded_answer | string | An answer to the user's question based on information in the product catalog record. |
| supporting_evidence | array | Catalog evidence supporting the answer, identifying the relevant product field and the text that provides support. |
| product_catalog_record | object | The original structured product catalog entry used as the source for answering the question. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

