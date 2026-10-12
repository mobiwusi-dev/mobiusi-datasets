---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Video Ad Script Constraint Validator Stress-Test Benchmark
---

# Video Ad Script Constraint Validator Stress-Test Benchmark

This benchmark contains paired compliant and near-miss synthetic video ad scripts, covering boundary word counts, omitted required phrases, concealed prohibited terms, and attempts to evade surface-level checks. It provides explicit constraint rules, itemized validation results, and reward outcomes to assess rule following in controlled advertising text generation. The benchmark supports research on reinforcement learning with verifiable rewards (RLVR) and helps identify failure modes in which models exploit gaps in validator rules.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| script_pair | object | A pair of original synthetic ad script texts, including a compliant example and a near-miss example, without encoding their verdicts in the field name. |
| reward_results | array | Reward outcomes for each script, calculated from the itemized validation results and reward rules. |
| failure_mode_label | string | A primary failure mode or stress-test label derived from the validation process to summarize validator weaknesses. |
| rule_specification | object | Original test rules and boundary conditions used to validate the scripts. |
| validation_results | array | Itemized verdicts and summary conclusions derived by applying the rules to each script in the pair. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

