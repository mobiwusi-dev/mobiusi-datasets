---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Dynamic Travel Package Assembly Code Generation Dataset
---

# Dynamic Travel Package Assembly Code Generation Dataset

This dataset pairs travelers' natural-language preferences, dates, budgets, and package requirements with catalogs of flight, accommodation, and activity options, along with reference code. The examples show how to filter candidate products and combine them into travel packages, supporting training and evaluation of models that interpret travel requests, work with product catalogs, and generate package assembly code. It covers the text-to-code workflow for dynamic travel packaging and is suited to code fine-tuning and application prototyping.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| user_request | string | Natural-language request describing the traveler's preferences, travel dates, budget, and package requirements. |
| reference_code | string | Reference implementation that filters and combines catalog products to assemble a travel package matching the request. |
| product_catalog | object | Available flight, accommodation, and activity options, including relevant details and prices. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

