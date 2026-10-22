---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Configuration Change Plan Constraint Verification Dataset
---

# Configuration Change Plan Constraint Verification Dataset

This JSON dataset describes IT configuration states, configuration-item dependencies, change requests, candidate operations, and ordering constraints, with annotations for plan validity, constraint checks, execution order, violations, and reward scores. Deterministic verification covers prerequisites, dependencies, operation ordering, and protected-state rules, supporting the training and evaluation of models that check configuration change plans for constraint compliance. The verification outcomes can also serve as verifiable reward signals for reinforcement learning with verifiable rewards.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| is_valid | boolean | Whether the proposed plan satisfies all evaluated prerequisites, dependencies, ordering constraints, and protected-state rules. |
| input_data | object | The source JSON data describing the configuration state, requested changes, candidate operations, and ordering constraints. |
| violations | array | Specific constraints that the proposed plan fails to satisfy. |
| reward_score | number | Deterministic score derived from the verification outcome for reinforcement learning with verifiable rewards. |
| check_results | object | Individual deterministic results for the principal constraint categories. |
| execution_order | array | Operation names in the proposed execution sequence, when an execution sequence is provided or can be derived. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

