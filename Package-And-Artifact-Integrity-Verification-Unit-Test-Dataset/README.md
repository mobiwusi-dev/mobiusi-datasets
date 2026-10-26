---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Package and Artifact Integrity Verification Unit Test Dataset
---

# Package and Artifact Integrity Verification Unit Test Dataset

Focused on integrity verification in package and artifact management, the dataset includes Python implementation code, task instructions, verification fixtures, and generated or repaired unit tests. Examples cover digest and checksum comparisons, signature verification, content mismatches, missing verification data, and invalid verification results. It supports training and evaluating code models for test generation and repair.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| test_code | string | The resulting Python unit test code after generation or repair. |
| source_code | string | Python implementation under test, including artifact digest, checksum, or signature verification logic. |
| task_prompt | string | Instructions for generating or repairing unit tests and the integrity behavior they must verify. |
| operation_type | string | Indicates whether the example generates new tests or repairs existing tests. |
| test_framework | string | The unit testing framework used by the resulting test code, such as pytest or unittest. |
| test_case_count | integer | The number of distinct test cases represented in the resulting test code. |
| primary_scenario | string | The main artifact integrity condition exercised by the unit test. |
| assertion_summary | string | A concise summary of the principal values, exceptions, or verification outcomes asserted by the tests. |
| existing_test_code | string | Python unit tests provided for repair; empty when the task is to generate tests. |
| expected_test_status | string | The expected outcome when the resulting test code runs against the intended implementation. |
| verification_fixtures | string | JSON-serialized fixtures such as artifact content, expected digests, checksums, and signatures. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

