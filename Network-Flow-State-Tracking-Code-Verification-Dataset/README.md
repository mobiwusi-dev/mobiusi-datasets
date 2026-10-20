---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Network Flow State Tracking Code Verification Dataset
---

# Network Flow State Tracking Code Verification Dataset

This dataset contains analysis source code that maintains network connection or flow state, accompanied by labels assessing state-update correctness and diagnosing issues. Annotations cover state lifecycles, timeout logic, out-of-order packet or event handling, state transitions, and diagnostic evidence. It supports training and evaluating models that verify session-tracking code, identify state errors, and assist with debugging network traffic analysis tools.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| root_cause | string | Summarizes the code logic or conditional check behind a state-tracking error; if no error is found, states the verification conclusion. |
| source_code | string | Analysis source code that maintains network session or flow state. |
| error_categories | array | Categories of state-tracking issues found in the code, potentially including lifecycle, timeout, out-of-order handling, or state-update errors. |
| timeout_assessment | string | Describes whether timeout conditions, timeout checks, and cleanup of expired state are correct. |
| diagnostic_evidence | string | Cites or describes code behavior, conditions, or execution scenarios that support the correctness judgment and root-cause conclusion. |
| lifecycle_assessment | string | Describes whether initialization, active maintenance, and termination cleanup of connection or flow state behave as expected. |
| programming_language | string | Programming language used by the source code. |
| state_update_correct | boolean | Indicates whether the code correctly creates, updates, and clears connection or flow state. |
| out_of_order_assessment | string | Describes whether handling out-of-order packets or events can cause state errors. |
| state_transition_summary | string | Summarizes key state variables and how they are updated and transitioned along relevant code paths. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

