---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Condensed Milk Formulation Composition Calculation Verification Dataset
---

# Condensed Milk Formulation Composition Calculation Verification Dataset

This dataset focuses on composition calculations for condensed milk formulations, covering ingredient masses and compositions, final product mass, submitted numerical claims, and calculated metrics such as fat, sugar, and total solids. Each sample can also record the calculation basis, whether the claim is correct, the error type, and a verification rationale. It supports training and evaluating models that check formulation calculations, as well as food formulation review and calculation verification workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| error_type | string | Classifies the detected issue, or indicates that there is no error when the submitted claim is correct. |
| submitted_claim | object | Numerical composition values submitted for verification, optionally accompanied by an absolute tolerance in percentage points. |
| is_claim_correct | boolean | Indicates whether the submitted values agree with the calculated values within the specified tolerance. |
| calculation_basis | string | The formula or a concise explanation used to calculate final product composition, such as dividing component mass by final product mass and multiplying by 100. |
| formulation_input | object | Ingredient masses and composition data, together with the final product mass used in the calculation. |
| calculated_metrics | array | Composition percentages calculated from ingredient masses, ingredient composition, and final product mass. |
| verification_rationale | string | Explains the correctness decision and any identified discrepancy. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

