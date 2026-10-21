---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Restaurant Order-to-Service Workflow Constraint Verification Dataset
---

# Restaurant Order-to-Service Workflow Constraint Verification Dataset

Designed for casual dining scenarios, this dataset provides text descriptions of table and seat assignments, ordered items, kitchen dependencies, and service states, alongside proposed order-handling, kitchen, and serving workflows. Each intermediate step is labeled for constraint compliance, with a focus on order ownership, action sequence, and state transitions. It supports process verifier training and evaluation by helping models identify violations during execution rather than judging only the final outcome.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| scenario_text | string | Text describing the restaurant context, including table and seat assignments, order items, kitchen dependencies, and relevant service states. |
| validation_steps | array | Constraint verification results for each intermediate workflow step. |
| violation_summary | string | Concise summary of workflow violations, or an empty string when the workflow is fully compliant. |
| proposed_workflow_text | string | Text describing the ordered sequence of order handling, kitchen, and service actions to be evaluated. |
| overall_workflow_compliant | boolean | Whether every evaluated step satisfies the applicable order ownership, operation sequence, and state transition constraints. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

