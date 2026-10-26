---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mixed-Signal System Fault Diagnosis Q&A Dataset
---

# Mixed-Signal System Fault Diagnosis Q&A Dataset

This dataset contains structured diagnostic Q&A for mixed-signal systems, covering symptom descriptions, measurement observations, and design conditions alongside likely causes, cross-module reasoning, discriminating tests, and verification plans. Its examples focus on relationships among circuit modules and signal-chain behavior, helping models connect multiple observations to plausible failure mechanisms and actionable troubleshooting steps. It supports mixed-signal circuit debugging, system verification, and domain-specific model training.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| likely_causes | array | Ranked plausible failure causes, with implicated modules, mechanisms, supporting evidence, and predicted measurement signatures. |
| design_conditions | string | Relevant design, configuration, operating, and environmental conditions for the system under investigation. |
| verification_plan | array | Ordered steps to confirm the leading diagnosis and assess whether corrective action resolves the failure. |
| diagnostic_summary | string | A concise expert conclusion summarizing the leading diagnosis, key rationale, and recommended next action. |
| symptom_description | string | Reported system or circuit symptoms, including operating context and timing. |
| discriminating_tests | array | Tests that distinguish among plausible causes, with expected results and their diagnostic meaning. |
| cross_module_reasoning | string | An explanation linking implicated circuit modules and signal-chain relationships to the observed failure, including dependencies and propagation effects. |
| measurement_observations | string | Observed measurements and signal behavior, including relevant values, trends, and measurement conditions. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

