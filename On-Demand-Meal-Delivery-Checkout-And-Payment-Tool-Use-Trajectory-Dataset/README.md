---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: On-Demand Meal Delivery Checkout and Payment Tool-Use Trajectory Dataset
---

# On-Demand Meal Delivery Checkout and Payment Tool-Use Trajectory Dataset

This dataset focuses on on-demand meal delivery transactions, capturing tool calls, returned results, and follow-up actions across checkout, coupon validation, fee confirmation, and payment processing. It includes chronologically ordered events and structured details such as checkout, promotion, fee, payment, and order statuses, along with the next required action. Use it to build and evaluate agents that reliably execute transaction workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| events | array | Derived events arranged in chronological order, including tool calls, tool results, and subsequent actions. |
| fee_summary | object | Derived item, delivery, tax, discount, and final-total amounts confirmed during checkout. |
| next_action | string | Derived next action required to continue or complete the order flow. |
| order_status | string | Derived final order state after checkout and payment processing. |
| payment_status | string | Derived payment outcome, such as not started, authorized, completed, or declined. |
| checkout_status | string | Derived status of the checkout process, such as pending, ready, or failed. |
| source_trajectory | object | The original tool-use trajectory record, preserved as the independent input source. |
| coupon_validation_status | string | Derived result of validating the applied coupon or promotion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

