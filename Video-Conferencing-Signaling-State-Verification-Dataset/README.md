---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Video Conferencing Signaling State Verification Dataset
---

# Video Conferencing Signaling State Verification Dataset

This dataset focuses on signaling state handling in enterprise video conferencing and includes source code for meeting creation, joining, leaving, reconnection, and termination, along with state-transition tests and defect samples. It covers verification workflows such as checking state logic, identifying illegal transitions, analyzing duplicate events, and tracing failure causes. Use it to train and evaluate code-verification and debugging capabilities and to improve the reliability of meeting state machines.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| suggested_fix | string | Recommended code or state-machine change to address the identified signaling defect. |
| defect_sample_code | string | Code containing a signaling state defect or a reproducible faulty event sequence. |
| root_cause_analysis | string | Explanation of the underlying logic or event-handling issue responsible for a verification failure. |
| verification_status | string | Overall outcome of state-logic verification, such as passed, failed, or inconclusive. |
| affected_state_names | array | Names of signaling states implicated by the verification findings. |
| signaling_source_code | string | Source code implementing signaling behavior for meeting creation, joining, leaving, reconnection, or termination. |
| verification_test_code | string | Test code for validating signaling state transitions and event handling. |
| duplicate_event_findings | array | Findings describing duplicate signaling events and their effects on state handling. |
| detected_illegal_transitions | array | State transitions identified as invalid under the expected signaling rules. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

