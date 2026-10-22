---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: NB-IoT Registration and Protocol State Reasoning Dataset
---

# NB-IoT Registration and Protocol State Reasoning Dataset

This dataset provides text-based protocol traces of NB-IoT device registration, including interaction events, connection-state changes, and procedure order. Question-answer examples ask models to identify the current state, detect an omitted step, or infer a plausible next state, with answers and reasoning explanations. It supports training and evaluation of logical understanding of NB-IoT protocol procedures.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | The direct answer to the question, including the relevant state, missing step, or next-state inference. |
| question | string | A question about the current connection state, a missing procedure step, or a plausible subsequent state. |
| reasoning | string | An explanation connecting the protocol events and their order to the answer. |
| task_type | string | The reasoning task category, such as state identification, missing-step detection, or next-state inference. |
| missing_step | string | The omitted registration or protocol step identified from the trace, or an empty string if no step is missing. |
| current_state | string | The connection or registration state inferred from the protocol trace, when applicable. |
| protocol_trace | string | Text describing the NB-IoT registration procedure, state changes, and interaction events. |
| predicted_next_state | string | The plausible next connection or registration state inferred from the described events. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

