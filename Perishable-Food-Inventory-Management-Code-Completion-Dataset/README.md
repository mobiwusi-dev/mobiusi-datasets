---
license: cc-by-nc-sa-4.0
task_categories:
- other
language:
- en
pretty_name: Perishable Food Inventory Management Code Completion Dataset
---

# Perishable Food Inventory Management Code Completion Dataset

This dataset contains code-completion examples for inventory management in specialty food retail, covering batch quantities, shelf-life dates, near-expiry status, and First-Expired, First-Out (FEFO) allocation logic. Each sample includes an incomplete code prefix, a reference continuation, and the concatenated complete code for supervised training and output verification. It supports supervised fine-tuning of code-generation models, code-completion training, and evaluation of inventory workflows for perishable goods.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| code_prefix | string | An incomplete code snippet for perishable food inventory management, typically providing context about batch quantities, shelf-life dates, near-expiry status, or FEFO handling. |
| completed_code | string | The complete code formed by concatenating the incomplete prefix and reference continuation in their original order. |
| reference_completion | string | The reference code continuation used as the supervised target to complete the inventory logic in the prefix. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

