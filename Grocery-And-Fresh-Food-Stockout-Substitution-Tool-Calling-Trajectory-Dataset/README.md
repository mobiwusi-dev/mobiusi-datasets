---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Grocery and Fresh Food Stockout Substitution Tool-Calling Trajectory Dataset
---

# Grocery and Fresh Food Stockout Substitution Tool-Calling Trajectory Dataset

This dataset covers grocery and fresh food delivery scenarios involving out-of-stock items, customer substitution preferences, and candidate replacements. It captures how requirements such as brand, price, product category, and dietary restrictions can be converted into parameters for substitute searches and confirmation actions. With source context and ordered target tool calls, it supports function-calling training, stockout workflow automation, and improvements to fulfillment in on-demand delivery.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_context | object | Original stockout information, customer instructions, and candidate substitute products provided as input. |
| target_tool_calls | array | Ordered tool invocations and parameter values derived from the source context to search for and confirm a substitute. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

