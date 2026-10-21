---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pelvic Floor Treatment and Surgery Eligibility Constraint Evaluation Benchmark
---

# Pelvic Floor Treatment and Surgery Eligibility Constraint Evaluation Benchmark

This JSON benchmark records patient conditions, required assessment information, and proposed management for pelvic floor treatments or procedures, alongside rule-based checks of applicability, prerequisites, and exclusions. It focuses on constraint verification in urogynecology and pelvic medicine, helping evaluate whether a model can assess multiple conditions and explain its reasoning rather than match a single label. No sample count is provided; the exact coverage depends on the delivered data.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | Structured source case information used to evaluate a proposed treatment or procedure against applicable constraints. |
| eligibility_assessment | object | Rule-based results derived from the source case, covering applicability, prerequisite checks, exclusion checks, and supporting explanations. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

