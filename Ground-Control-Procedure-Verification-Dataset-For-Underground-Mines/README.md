---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Ground-Control Procedure Verification Dataset for Underground Mines
---

# Ground-Control Procedure Verification Dataset for Underground Mines

Designed for ground-control scenarios in underground gold-silver polymetallic mines, this dataset contains text describing geological and operational conditions, candidate support and excavation steps, and checks of step order, measure applicability, and omitted controls. The examples help models determine whether a proposed procedure violates explicitly stated ground-control constraints, supporting the training and evaluation of specialized step verifiers and process verification models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_verdict | string | Overall determination of whether the candidate sequence violates any explicitly stated ground-control constraint. |
| candidate_sequence | string | Original proposed support and excavation steps, in the order presented for verification. |
| scenario_conditions | string | Original geological and operational conditions provided for the underground mine scenario. |
| violated_constraints | array | Explicit ground-control constraints violated by the candidate sequence. Use an empty array if no violations are found. |
| stepwise_verification | array | Ordered findings that check each candidate step against the relevant conditions and constraints. |
| verification_rationale | string | Concise explanation linking the conditions, candidate steps, and explicit constraints to the final verdict. |
| applicability_assessment | string | Assessment of whether each proposed measure suits the stated geological and operational conditions. |
| omitted_control_measures | array | Ground-control measures required by the explicit constraints but missing from the candidate sequence. |
| sequence_order_assessment | string | Assessment of whether the proposed support and excavation steps follow the required order. |
| ground_control_constraints | string | Original task constraints governing step order, applicability, and required control measures. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

