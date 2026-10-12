---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Ship Weight and Center of Gravity Calculation Verification Dataset
---

# Ship Weight and Center of Gravity Calculation Verification Dataset

Designed for commercial ship design and construction, this dataset provides weight-item inputs organized by equipment, structure, and other categories, together with calculated totals, moments, and center-of-gravity positions. The JSON samples include reference results, calculation tolerances, and correctness labels to train and evaluate verifiers for weight estimates, moment aggregation, and center-of-gravity calculations. Typical uses include checking ship design calculations, developing result-validation workflows, and training related models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| weight_items | array | Input details for equipment, structural, and other items included in the vessel weight estimate. |
| vessel_context | object | Background information for the vessel and weight estimate, such as the coordinate system and design stage. |
| reference_results | object | Baseline aggregate values, calculation tolerances, and correctness labels provided for comparison during verification. |
| calculated_results | object | Total weight, total moments in each direction, and center-of-gravity positions calculated from the weight items. |
| validation_results | object | Errors and validation conclusions produced by comparing calculated summary results with reference results and tolerances. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

