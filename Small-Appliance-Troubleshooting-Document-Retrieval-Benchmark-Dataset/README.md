---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Small Appliance Troubleshooting Document Retrieval Benchmark Dataset
---

# Small Appliance Troubleshooting Document Retrieval Benchmark Dataset

This dataset pairs queries describing small appliance malfunctions or usage problems with candidate web documents, including retailer support pages, FAQs, and troubleshooting guides, and provides relevance labels for each query-document pair. It focuses on knowledge retrieval and query-document matching in small appliance retail after-sales support. Use it to evaluate how well models retrieve suitable troubleshooting resources and to build or validate document retrieval systems. The specific product coverage and dataset size depend on the records provided.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| document | object | A retailer support page, FAQ, or troubleshooting guide that may help answer the query. |
| query_text | string | A user's description of a small appliance malfunction or usage problem. |
| relevance_label | integer | The relevance level of the candidate document to the query; the dataset annotation guidelines define the specific values. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

