---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Workflow DAG Scheduling Code Understanding Dataset
---

# Workflow DAG Scheduling Code Understanding Dataset

This dataset covers source code for workflow task dependency graph construction, dependency readiness checks, topological processing, and downstream task triggering. It pairs relevant scheduling code excerpts with supervised questions and answers about dependencies and execution behavior. The content supports code fine-tuning, source code question answering, and evaluation of scheduling logic understanding in distributed task and job scheduling systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct answer grounded in the provided source code. |
| question | string | A question about the DAG logic or execution behavior shown in the source code. |
| source_code | string | A code excerpt implementing workflow DAG construction, dependency checks, topological processing, or downstream task scheduling. |
| execution_behavior | string | An explanation of how the code schedules or triggers successor tasks, including relevant conditions and state changes. |
| dependency_analysis | string | An explanation of how the code represents task dependencies, checks readiness, or processes tasks in topological order. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

