---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: API Unit Test Repair Dataset
---

# API Unit Test Repair Dataset

This dataset pairs API implementation or interface changes with unit tests that fail after those changes and repaired test code aligned with the updated API behavior. Examples cover common repairs such as assertion updates, mock or stub adjustments, and interface adaptation, with a repair category and explanation for each case. The data supports training code models to generate repaired tests and can also be used for regression validation and test maintenance during API evolution.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| repair_category | string | A concise classification of the repair, such as an assertion update, mock or stub adjustment, or interface adaptation. |
| api_change_context | string | A description or diff of API implementation or interface changes relevant to the test failure. |
| repair_explanation | string | A brief explanation of why the original test failed and how the repaired test resolves the issue. |
| repaired_test_code | string | Corrected unit test code updated to match the changed API behavior or interface. |
| failing_unit_test_code | string | The original unit test code that fails after or in the context of the API change. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

