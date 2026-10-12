---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Automotive Lighting State Machine Code Reasoning Benchmark
---

# Automotive Lighting State Machine Code Reasoning Benchmark

This benchmark focuses on mode management and state transitions in automotive lighting ECUs, pairing relevant source code with annotations of state machine behavior. It covers state names, transition events and conditions, and lighting control or other ECU outputs associated with each state. Use it to assess whether models can reconstruct state behavior and key transition logic from code, and to evaluate code understanding and reasoning in automotive lighting electronics.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | Original source code related to lighting ECU mode management and state transitions. |
| state_names | array | A list of state names identified in the source code. |
| transitions | array | State transitions reconstructed from the source code, including their triggering events and transition conditions. |
| state_outputs | array | Lighting control outputs or other ECU output behavior summarized for each state. |
| behavior_summary | string | A summary of the state machine's overall behavior, key transition paths, and output logic. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

