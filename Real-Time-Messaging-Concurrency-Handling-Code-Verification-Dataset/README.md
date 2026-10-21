---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Real-Time Messaging Concurrency Handling Code Verification Dataset
---

# Real-Time Messaging Concurrency Handling Code Verification Dataset

Designed for real-time collaboration features in team channel and workgroup software, this dataset contains source code and verification cases for message delivery, status updates, and concurrent processing. Each case covers expected behavior, verification results, defect type and location, root-cause analysis, concurrency behavior, and a suggested fix, with a focus on race conditions and inconsistent state handling. It supports training and evaluating code verification, defect localization, and root-cause analysis, helping improve the reliability of real-time messaging logic.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| root_cause | string | Underlying logic or synchronization error that caused verification to fail. |
| defect_type | string | Category of any concurrency or state-handling defect identified during verification. |
| source_code | string | Messaging code submitted for verification. |
| suggested_fix | string | Concise code-level recommendation for correcting the identified defect. |
| defect_location | object | Source location associated with the identified defect, when applicable. |
| verification_goal | string | Expected behavior or property to check in the messaging code. |
| concurrency_analysis | string | Analysis of relevant operation interleavings, shared state, and message-processing behavior. |
| verification_outcome | string | Result of checking the code against the stated verification goal. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

