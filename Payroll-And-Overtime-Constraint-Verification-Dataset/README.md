---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Payroll and Overtime Constraint Verification Dataset
---

# Payroll and Overtime Constraint Verification Dataset

Each JSON record captures a payroll period, regular and overtime hours, pay components, and the applicable human-resources rule version, alongside a candidate calculation, an independently computed result, and individual constraint checks. The records support training and evaluating models that verify payroll and overtime calculations against stated rules, with deterministic checks providing auditable reward signals. They are suited to human capital management, payroll automation, and research on reinforcement learning with verifiable rewards.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| is_valid | boolean | Whether all required payroll and overtime constraints pass within the configured comparison tolerance. |
| pay_period | object | The date range and payroll frequency associated with the record. |
| work_hours | object | Recorded regular, overtime, and total hours for the payroll period. |
| reward_score | number | The deterministic reward assigned to the verification result, typically one for a valid calculation and zero otherwise. |
| overtime_rule | object | The applicable human-resources rule version and parameters for overtime pay. |
| pay_components | object | Source rates and other amounts used in the candidate payroll calculation. |
| constraint_checks | object | Individual deterministic checks comparing the recorded data and candidate results with the applicable payroll constraints. |
| expected_calculation | object | Payroll amounts independently computed from the source inputs and overtime rule. |
| candidate_calculation | object | The proposed monetary results to be checked against the recorded hours, pay components, and applicable rule. |
| calculation_differences | object | Signed differences between candidate and independently computed amounts, expressed in the record currency. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

