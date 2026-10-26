---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Function-Level Unit Test Generation Dataset
---

# Function-Level Unit Test Generation Dataset

Each record pairs function or method source code with corresponding executable unit tests covering typical behavior, boundary inputs, and exception paths. The examples can support training and evaluation of models that interpret code, generate test cases, and translate testing requirements into code. The dataset is suited to developer tools, automated testing, and code generation; actual dataset size and programming-language coverage depend on the available records.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | Original function or method source code provided as input. Python is used as the representative code MIME type when the source language is unspecified. |
| generated_test_code | string | Executable unit test code generated for the source function or method, covering typical behavior, boundary inputs, and exception paths. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

