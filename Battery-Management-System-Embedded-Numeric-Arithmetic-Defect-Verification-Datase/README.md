---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Battery Management System Embedded Numeric Arithmetic Defect Verification Dataset
---

# Battery Management System Embedded Numeric Arithmetic Defect Verification Dataset

This dataset contains verification examples from battery management system (BMS) source code involving fixed-point arithmetic, unit conversions, integer overflow, truncation, and numeric range handling. Examples capture test conditions, expected behavior, and observed failures, with annotations for defect categories, affected expressions, and code-level root causes. Suggested corrections and verification assertions support training and evaluating models for detecting embedded arithmetic defects, tracing their causes, and assisting with code fixes.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| root_cause | string | The implementation-level reason the defect occurs, including relevant type, scaling, conversion, or range-handling details. |
| source_code | string | The BMS source-code snippet being verified, including the relevant arithmetic implementation. |
| test_case_json | string | A JSON-encoded test case containing relevant input values, units, expected behavior, and any applicable numeric limits or tolerances. |
| defect_category | string | The primary category of the identified numeric defect. |
| defect_confirmed | boolean | Indicates whether verification confirms an arithmetic or numeric-handling defect in the source code. |
| observed_failure | string | The incorrect result or runtime behavior observed during verification, such as wraparound, unexpected truncation, or a unit-scale mismatch. |
| numeric_signedness | string | The signedness of the numeric representation relevant to the defect. |
| numeric_width_bits | integer | The relevant integer or fixed-point storage width in bits when it can be determined from the source or verification case. |
| affected_expression | string | The source expression or short code fragment identified as the location of the defect. |
| arithmetic_operation | string | The arithmetic operation or conversion most directly involved in the defect. |
| corrected_expression | string | A suggested corrected expression or implementation fragment that addresses the identified defect. |
| remediation_guidance | string | A concise explanation of the changes needed to correct the defect and avoid similar numeric errors. |
| verification_assertion | string | A concise assertion or expected condition that can be used to verify the implementation after correction. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

