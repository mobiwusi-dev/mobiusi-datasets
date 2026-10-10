---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: 5G Core Network Protocol Encoding and Decoding and Information Element Code Verification Benchmark
---

# 5G Core Network Protocol Encoding and Decoding and Information Element Code Verification Benchmark

This benchmark contains source code examples related to 5G core network protocol message encoding and decoding, as well as information element parsing and validation. It focuses on defect-prone cases involving length handling, optional fields, and boundary conditions. Each case pairs test inputs with expected constraints and records validation results, defect categories, affected information elements, root causes, and code evidence, supporting evaluation of models' protocol verification and root-cause analysis capabilities.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence | string | Code location, key logic, or validation observation supporting the defect finding. |
| test_case | object | Original test input and expected constraints used to verify protocol handling behavior. |
| source_code | string | Source code to verify for protocol encoding and decoding or information element parsing and validation. |
| bug_root_cause | string | Code logic or constraint handling that causes protocol behavior to deviate from expectations. |
| defect_category | string | Category of the identified protocol handling defect. |
| validation_result | string | Whether code execution or rule checking conforms to the expected constraints. |
| affected_information_element | string | Name of the information element with a parsing, encoding, or validation issue; use unknown when it cannot be determined. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

