---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Repository-Context-Aware Unit Test Generation Dataset
---

# Repository-Context-Aware Unit Test Generation Dataset

Each sample pairs target source code with repository context, including the target file path, relevant module interfaces, existing test conventions, repository information, and generated unit tests; programming language and test framework are also identified. The examples help models learn to account for dependencies, project configuration, and established testing practices when writing tests for real codebases. The dataset is suited to code supervised fine-tuning, developer tool training, and evaluation of unit test generation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| target_code | string | The source code under test, written in the repository's programming language. |
| test_framework | string | The test framework used by the generated unit tests, inferred from repository context and existing test conventions. |
| target_file_path | string | The repository-relative path to the target source file. |
| repository_context | string | Additional repository information needed to understand dependencies, configuration, and test setup. |
| generated_test_code | string | Unit test code generated for the provided target code and repository context. |
| programming_language | string | The language used by the target code and generated unit tests. |
| existing_test_conventions | string | Project-specific testing patterns, assertions, fixtures, and framework conventions. |
| related_module_interfaces | string | Relevant dependency declarations, module interfaces, and API signatures required to understand the target code. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

