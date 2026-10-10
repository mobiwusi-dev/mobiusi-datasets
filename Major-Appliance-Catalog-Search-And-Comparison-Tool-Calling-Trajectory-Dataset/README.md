---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Major Appliance Catalog Search and Comparison Tool-Calling Trajectory Dataset
---

# Major Appliance Catalog Search and Comparison Tool-Calling Trajectory Dataset

This dataset captures sequences of catalog search and product comparison tool calls made in response to customer requests to find, filter, or compare major appliances. It includes the original request, an intent summary, tool arguments and results, candidate product specifications, and comparison conclusions. The data supports training and evaluating models on intent understanding, tool selection, argument construction, and multi-step product discovery in major appliance retail, as well as analysis of tool-use workflows and recommendation results.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| tool_trace | object | An ordered record of catalog search and product comparison tool calls, including arguments, results, and subsequent calls. |
| task_status | string | Indicates whether the product discovery task was completed or could not be fully completed. |
| intent_summary | string | A summary of the product category, filtering preferences, and comparison goals inferred from the customer's original request. |
| customer_request | string | The customer's original request to search for, filter, or compare products. |
| product_comparison | array | Candidate products and their key specifications, organized from tool results for side-by-side comparison. |
| comparison_conclusion | string | Differences among candidate products and recommendation rationale based on search results and customer preferences. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

