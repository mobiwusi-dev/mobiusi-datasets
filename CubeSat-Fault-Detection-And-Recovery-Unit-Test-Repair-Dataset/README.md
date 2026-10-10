---
license: cc-by-nc-sa-4.0
task_categories:
- other
language:
- en
pretty_name: CubeSat Fault Detection and Recovery Unit Test Repair Dataset
---

# CubeSat Fault Detection and Recovery Unit Test Repair Dataset

This dataset contains small-satellite flight software functions for fault detection, fault-state updates, and recovery, along with flawed and repaired unit tests for those functions. Examples cover common issues such as missing assertions, incorrect test inputs, and mismatched mock dependencies. The training objective is to generate repaired tests that verify fault-handling branches and expected state changes, supporting code SFT, spacecraft fault-handling test generation, and unit test repair.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| repair_summary | string | Summary of the test code changes and the fault-handling behavior verified after repair. |
| flawed_test_code | string | Original unit test code with issues such as missing assertions, incorrect test inputs, or mismatched mock dependencies. |
| fault_handler_code | string | Source code for the fault detection, fault-state update, or recovery function to be tested. |
| repaired_test_code | string | Unit test code repaired to verify fault-handling branches and expected state changes. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

