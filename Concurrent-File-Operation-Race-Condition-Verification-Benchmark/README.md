---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Concurrent File Operation Race Condition Verification Benchmark
---

# Concurrent File Operation Race Condition Verification Benchmark

This benchmark contains source code tasks and repair objectives involving concurrent reads and writes, lock management, cache updates, file closure, and metadata access in distributed file systems. Its task contexts and test setups are designed to assess whether code exhibits races, deadlocks, or inconsistent shared state under concurrent execution. It supports evaluation of code agents' defect detection, repair, and execution verification capabilities.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | Concurrent file operation source code or code snippets to be analyzed and verified. |
| task_context | string | Describes the file system scenario, concurrent participants, thread or process relationships, and relevant runtime conditions. |
| repair_objective | string | Describes the concurrency defect to fix, the intended direction of changes, and the correctness requirements. |
| concurrency_risks | array | A list of concurrency risk types identified from the source code and task description. |
| validation_criteria | array | Observable conditions and test outcomes used to determine whether a repair is effective. |
| programming_language | string | The primary programming language identified from the source code. |
| concurrency_test_setup | string | Describes the test triggers, concurrent scheduling, read and write order, lock operations, cache state, or file lifecycle conditions used for verification. |
| deadlock_risk_detected | boolean | Indicates whether lock ordering, release paths, and blocking relationships suggest a deadlock risk. |
| race_condition_detected | boolean | Indicates whether analysis or testing found unsynchronized concurrent reads, writes, or state updates. |
| expected_correct_behavior | string | Describes the behavior that should remain correct under concurrent execution, exceptional paths, and file lifecycle changes after repair. |
| operation_and_lock_summary | string | Summarizes key interactions among file reads and writes, lock acquisition and release, cache updates, file closure, and metadata access. |
| repair_verification_summary | string | Summarizes repair performance in concurrency tests and notes boundary conditions or residual risks that may require attention. |
| state_consistency_risk_detected | boolean | Indicates whether concurrent operations may leave caches, file metadata, file handles, or other shared state inconsistent. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

