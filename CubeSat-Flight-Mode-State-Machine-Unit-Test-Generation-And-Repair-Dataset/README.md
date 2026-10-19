---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: CubeSat Flight Mode State Machine Unit Test Generation and Repair Dataset
---

# CubeSat Flight Mode State Machine Unit Test Generation and Repair Dataset

Designed for small-satellite and CubeSat flight software, this dataset provides state machine source code, test task instructions, transition scenarios, expected behavior, and corresponding Python unit tests and assertion examples. It covers normal transitions, invalid transitions, and safety-mode paths, with tasks for both test generation and assertion repair. The dataset supports code SFT and evaluation of models that generate or repair tests based on spacecraft operating-mode logic; the number of examples depends on the supplied package.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| task_type | string | The target task type inferred from the task instructions. |
| task_prompt | string | The original instructions for test generation or assertion repair. |
| unit_test_code | string | Target unit test code in Python format, expressing the test scenarios and assertions. |
| repair_rationale | string | For assertion repair tasks, explains the issue with the original assertion and the basis for the correction; may be an empty string for generation tasks. |
| transition_cases | array | State transitions, trigger conditions, and expected behavior organized from the state machine logic for testing. |
| expected_behavior | string | A brief description of expected behavior on the test path, including state changes, rejection of invalid requests, or safety protections. |
| expected_assertions | array | Key conditions or assertions that the unit test should verify. |
| implementation_source | string | Original source code for the state machine, preserving the programming language and code content in the example. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

