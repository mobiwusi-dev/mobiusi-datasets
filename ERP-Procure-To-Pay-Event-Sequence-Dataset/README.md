---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: ERP Procure-to-Pay Event Sequence Dataset
---

# ERP Procure-to-Pay Event Sequence Dataset

Covers events across the ERP procure-to-pay process, including purchase requisitions, approvals, purchase orders, goods receipt, invoice matching, and payment, showing how procurement cases evolve through business states. The data provides raw case sequences, next-event targets for prediction, and summary features derived from observed sequence prefixes to support state-transition analysis and future event prediction. It is suited to procurement process mining, accounts payable analysis, and enterprise process improvement.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_data | object | Source event sequence and the boundary that defines the prediction context. |
| next_event_target | object | Target label derived from the event immediately following the observed prediction context. |
| sequence_features | object | Summary features calculated from the observed event prefix. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

