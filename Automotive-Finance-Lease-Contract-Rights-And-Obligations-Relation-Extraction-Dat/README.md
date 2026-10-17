---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Automotive Finance Lease Contract Rights and Obligations Relation Extraction Dataset
---

# Automotive Finance Lease Contract Rights and Obligations Relation Extraction Dataset

This dataset compiles public FAQ pages, contract explanations, and customer guides from automotive finance leasing companies, with annotations for parties and rights-and-obligations relations involving vehicles, payments, maintenance, ownership, purchase options, and contract termination. It includes webpage content, source URLs, identified contract parties, and extracted relations such as rights, duties, permissions, and restrictions. Use it to fine-tune models for contract relation extraction from web text, support leasing information workflows, and develop related knowledge retrieval systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| parties | array | Identified parties and other entities involved in the leasing terms. |
| source_url | string | URL of the webpage containing the source contract information. |
| webpage_content | string | Original HTML content from a public leasing FAQ, contract explanation, or customer guide webpage. |
| contract_relations | array | Extracted relations describing rights, duties, permissions, and restrictions under the leasing terms. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

