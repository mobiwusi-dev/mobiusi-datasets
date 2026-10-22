---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: ERP Inventory Movement and State Invariant Validation Dataset
---

# ERP Inventory Movement and State Invariant Validation Dataset

This dataset uses structured JSON to describe inventory receipts, issues, transfers, batch or location changes, and related inventory snapshots, covering common ERP inventory movement scenarios. Each example can be used to check constraints such as quantity conservation, source and destination location consistency, batch traceability, and stock availability, with machine-readable violations as output. It provides explicit validation signals for verifiable-reward reinforcement learning and supports inventory constraint validation, model training, and evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| violations | array | Machine-readable violations found when validating the movement and its resulting inventory state. |
| movement_input | object | The original movement record and related inventory snapshots provided for validation. |
| validation_status | string | The overall result derived from the inventory invariant checks. |
| availability_check | object | A computed check that the movement does not consume more available stock than is held at the source location. |
| batch_traceability_valid | boolean | Indicates whether batch identifiers are tracked consistently between the movement and its inventory snapshots. |
| location_transition_valid | boolean | Indicates whether the recorded source and destination locations are consistent with the movement and inventory snapshots. |
| quantity_conservation_check | object | A computed comparison of the expected net quantity change with the actual change shown in the inventory snapshots. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

