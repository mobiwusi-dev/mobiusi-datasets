---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Simulation Configuration Consistency and Diagnosis Dataset
---

# Simulation Configuration Consistency and Diagnosis Dataset

This dataset contains parseable JSON simulation configurations, with a focus on conflicts in physical constraints, incompatible conditions, and invalid parameter combinations. Each record provides a consistency judgment, a diagnostic summary, conflict locations, and scientific rationale, along with the issues' potential effects on simulation execution and result reliability. It supports training and evaluating models for simulation configuration validation, scientific reasoning, and diagnostic explanation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| findings | array | An itemized record of identified configuration issues, their locations, and the scientific rationale. |
| is_consistent | boolean | Indicates whether the physical constraints, conditions, and parameter combinations in the configuration are mutually compatible. |
| diagnosis_summary | string | A brief explanation of the configuration issues and their main causes. |
| overall_recommendation | string | Overall recommendations for correcting or reviewing the configuration issues. |
| simulation_config_json | string | The original simulation configuration, provided as parseable JSON text. |
| overall_simulation_impact | string | Summarizes the combined effects of the identified issues on simulation runnability, stability, or result reliability. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

