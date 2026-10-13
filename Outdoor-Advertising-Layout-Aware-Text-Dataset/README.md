---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Outdoor Advertising Layout-Aware Text Dataset
---

# Outdoor Advertising Layout-Aware Text Dataset

This synthetic text dataset covers outdoor advertising formats such as billboards, digital screens, lightboxes, and wall ads, with content including headlines, body copy, calls to action, and disclaimers. Samples are organized around verifiable constraints such as line length, field order, hierarchy markers, screen-carousel character limits, and text integrity, supporting the training and evaluation of controlled text generation models for outdoor layouts. Structured inputs, generated outputs, and validation summaries also help assess whether a model follows layout requirements.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| layout_request | object | Original input containing ad copy, display medium, and layout constraints. |
| text_integrity | boolean | Indicates whether original text, including the headline, body copy, call to action, and disclaimer, is preserved in the derived layout. |
| carousel_segments | array | Text segments created by splitting ad copy to meet digital screen carousel character limits. |
| field_order_result | array | The order in which advertising fields appear in the derived text. |
| validation_summary | object | Validation results for constraints such as line length, field order, carousel character counts, and text integrity. |
| line_length_metrics | object | Derived character counts for lines in each advertising field. |
| hierarchy_annotation | string | Text representation with hierarchy markers for the headline, body copy, call to action, and disclaimer. |
| formatted_layout_text | string | Complete advertising text with line breaks arranged for the target outdoor layout. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

