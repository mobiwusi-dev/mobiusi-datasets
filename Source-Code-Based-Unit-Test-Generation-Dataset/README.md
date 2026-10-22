---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Source Code-Based Unit Test Generation Dataset
---

# Source Code-Based Unit Test Generation Dataset

This dataset pairs source code for functions or classes with descriptions of their expected behavior and corresponding unit test code. Examples cover test structure, framework conventions, and assertion writing, supporting model training to interpret code and generate tests that verify intended behavior. It is suited to code supervised fine-tuning, test-generation evaluation, and software quality tool development.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | The function or class implementation to be tested. |
| unit_test_code | string | Unit test code that exercises the source code and checks its expected behavior using appropriate test structure and assertions. |
| expected_behavior | string | A description of the intended behavior and relevant cases the tests should cover. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

