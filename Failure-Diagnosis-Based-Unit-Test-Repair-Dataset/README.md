---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Failure-Diagnosis-Based Unit Test Repair Dataset
---

# Failure-Diagnosis-Based Unit Test Repair Dataset

Each example includes the implementation under test, its original unit test, failure diagnostics such as compiler errors or runtime exceptions, and the repaired test with a concise repair summary. The data covers common issues including compilation failures, runtime errors, and assertion failures, teaching models to repair tests while leaving the implementation unchanged. It supports code supervised fine-tuning, software testing tool development, and evaluation of test repair in quality engineering workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| target_code | string | Source code for the implementation under test, provided as a code snippet. |
| repair_summary | string | A concise explanation of the test changes and how they address the reported diagnostics. |
| failure_category | string | The primary category of the reported failure. |
| existing_test_code | string | The original unit test code that must be repaired to address the reported failure. |
| repaired_test_code | string | The corrected unit test code. The implementation under test must remain unchanged. |
| failure_diagnostics | string | Compiler errors, runtime exceptions, assertion failures, or other diagnostic output associated with the existing test. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

