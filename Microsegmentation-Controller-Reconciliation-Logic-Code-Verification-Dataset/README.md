---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Microsegmentation Controller Reconciliation Logic Code Verification Dataset
---

# Microsegmentation Controller Reconciliation Logic Code Verification Dataset

Focused on microsegmentation controller reconciliation, the collection includes source code for reading desired policies, computing policy differences, applying updates, and recording execution state, together with verification scenarios and expected behavior. It covers key cases such as retries, partial failures, and drift between desired and executed state, supporting control-flow tracing and checks for omitted or incorrectly applied isolation policies. It is suitable for code reasoning and controller implementation verification, including assessment of policy consistency under failure conditions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| verification_case | object | An input scenario and its expected behavior for assessing the controller's reconciliation logic. |
| reconciliation_flow | array | An ordered description of relevant control-flow steps inferred from the source code. |
| verification_result | object | A judgment on whether the implementation satisfies the verification case and preserves its isolation invariant. |
| policy_diff_analysis | object | Analysis of how the controller obtains desired and observed state, computes differences, and applies policy updates. |
| controller_source_code | string | Source code that implements desired-policy reads, reconciliation, and execution-state updates. |
| failure_handling_analysis | object | Analysis of retry behavior, partial failures, and drift between desired and executed state. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

