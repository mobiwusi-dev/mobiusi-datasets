---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Sportswear Cart and Checkout Tool-Use Trajectory Dataset
---

# Sportswear Cart and Checkout Tool-Use Trajectory Dataset

This dataset contains tool-use trajectories for sportswear shopping, covering product variant selection by style, color, and size, adding items to a cart, reviewing cart contents, and performing pre-checkout actions. Each trajectory can capture the order of tool calls, returned results, cart items and quantities, and the final checkout state; the dataset size is not specified. It supports training and evaluating models on passing product parameters, tracking cart state, and following transaction steps in the correct order.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| tool_calls | array | The ordered sequence of tool calls and their returned results. |
| task_intent | string | A concise description of the shopper's intended cart or pre-checkout task. |
| cart_contents | array | The product variants and quantities identified in the cart after the recorded operations. |
| raw_trajectory | string | The original serialized conversation and tool-use trace for the cart and checkout task. |
| checkout_status | object | The observed cart and checkout state at the end of the trajectory, before any final purchase is completed. |
| sequence_validation | object | Computed checks on whether the trajectory follows the expected shopping and pre-checkout operation order. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

