---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Consensus Membership Change Code Verification Dataset
---

# Consensus Membership Change Code Verification Dataset

This dataset covers source code for member additions, removals, and configuration changes in distributed consensus systems. It focuses on quorum calculations, configuration state transitions, and joint consensus logic, pairing faulty code with code for reproducing issues or validating behavior. Structured scenario details support coding agent training for diagnosing membership-change failures and checking whether repairs preserve consistency constraints.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| change_context | string | Input context and triggering conditions for a membership change, configuration transition, or joint consensus scenario. |
| change_operation | string | The operation represented in the code, such as adding or removing a member, changing a configuration, or using joint consensus. |
| faulty_code_source | string | Source code containing defects related to member additions, removals, or configuration changes. |
| quorum_constraints | array | Quorum calculation rules and consistency constraints that must be met during membership changes. |
| validation_outcome | string | Summary of validation execution results and whether the fix passes the relevant checks. |
| root_cause_analysis | string | Analysis of the underlying cause of a membership-change failure based on the faulty code and scenario. |
| validation_code_source | string | Test and validation code used to reproduce failures or assess fixes for membership changes. |
| repair_consistency_assessment | string | Assessment of whether the repair preserves correct configuration transitions, quorum requirements, and consistency constraints. |
| configuration_transition_summary | string | Summary of the relationship between the old, new, and intermediate configurations and the state transition process. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

