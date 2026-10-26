---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Food and Allergen Compliance Agent Evaluation Benchmark
---

# Food and Allergen Compliance Agent Evaluation Benchmark

This benchmark covers event catering delivery and includes structured evaluation records with event, order, menu, dietary restriction, allergen, and delivery information, alongside agent trajectories and expected outcomes. It helps assess whether agents retain and correctly follow catering constraints, with cross-record checks across orders, menus, and delivery details. Use it to evaluate constraint adherence, compliance decisions, and execution quality in event catering agents.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| failure_reasons | array | Derived explanations of any missed, violated, or unverifiable constraints. |
| benchmark_record | object | The original benchmark input, including relevant event, order, menu, dietary restriction, allergen, delivery, agent trajectory, and expected-result information. |
| compliance_score | number | A derived numeric score representing the proportion of evaluated constraints satisfied by the agent. |
| compliance_status | string | The derived overall assessment of whether the agent's actions satisfy the benchmark constraints. |
| evaluation_summary | string | A concise derived explanation of the agent's performance and the evidence supporting the assessment. |
| cross_record_checks | array | Derived results from reconciling relevant order, menu, and delivery information against the benchmark constraints. |
| constraint_inventory | array | A derived list of dietary, allergen, menu, order, and delivery constraints identified in the benchmark record. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

