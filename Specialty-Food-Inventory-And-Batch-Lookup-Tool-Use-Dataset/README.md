---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Specialty Food Inventory and Batch Lookup Tool-Use Dataset
---

# Specialty Food Inventory and Batch Lookup Tool-Use Dataset

This dataset contains user requests and tool-use trajectories for inventory lookups in specialty food retail, covering product availability, store locations, and batch status. The trajectories record tool parameters, call order, and returned results as JSON text, alongside organized inventory records, user-facing answers, and summaries of supporting evidence. It is suited to training and evaluating models to interpret inventory requests, select the right lookup dimensions, handle multi-step tool results, and answer with evidence.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_answer | string | An inventory lookup response for the user that clearly states the results without making claims beyond the tool results. |
| user_request | string | The user's request to look up product inventory, store location, or batch status. |
| evidence_summary | string | A summary of the tool results supporting the final answer, including relevant products, stores, quantities, or batch statuses. |
| inventory_records | array | Records organized from tool results, including products, stores, available quantities, and batch statuses. |
| tool_interaction_trace | string | JSON text recording the parameters, sequence, and returned results of inventory, store, and batch tool calls. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

