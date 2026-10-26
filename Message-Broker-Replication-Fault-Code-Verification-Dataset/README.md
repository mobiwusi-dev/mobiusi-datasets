---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Message Broker Replication Fault Code Verification Dataset
---

# Message Broker Replication Fault Code Verification Dataset

This dataset contains source code samples related to replication, log synchronization, and leader failover in message brokers. It covers correct implementations and defective implementations that may cause inconsistent replica states, along with verification results and analysis details. Fields may include defect locations, root-cause explanations, verification evidence, and target repair code, making the dataset suitable for training and evaluating models that detect replication-path errors, analyze distributed state anomalies, and assist with code repair.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| root_cause | string | An explanation of how the implementation can cause replication errors or inconsistent replica states. |
| source_code | string | The original code sample that implements or participates in replication, log synchronization, or leader failover. |
| defect_location | string | The identified defect location, such as a function, code region, or line range; an empty string indicates that no defect was identified. |
| source_language | string | The programming language used in the source code sample, when known. |
| repair_target_code | string | The corrected code or targeted code change, when a repair is provided; otherwise, an empty string. |
| verification_outcome | string | The derived classification of the implementation as correct, defective, or inconclusive. |
| verification_rationale | string | The reasoning or evidence supporting the verification outcome, including relevant replication and leader transition behavior. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

