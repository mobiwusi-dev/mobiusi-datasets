---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Community Health Program Plan Constraint Validation Benchmark
---

# Community Health Program Plan Constraint Validation Benchmark

Structured JSON cases represent community health program plans, applicable rules, and available resources, covering key conditions such as service coverage targets, staff capabilities, budgets, service areas, and accessibility. Each case indicates whether a plan satisfies the constraints and records specific conflict categories with supporting evidence. The benchmark supports evaluation of constraint reasoning, compliance assessment, and conflict identification, as well as comparisons between models and validation of public health planning tools.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_input | object | The original JSON input containing the program plan, applicable rules, and available resources. |
| is_compliant | boolean | Whether the program plan satisfies all applicable coverage, staffing, budget, geographic, and accessibility constraints. |
| conflict_items | array | Specific constraints violated by the plan, with the relevant category and evidence. This array is empty when no conflicts are found. |
| validation_summary | string | A concise summary of the assessment and the principal reasons for the compliance result. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

