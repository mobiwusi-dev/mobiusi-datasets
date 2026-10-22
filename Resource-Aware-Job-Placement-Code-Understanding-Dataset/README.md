---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Resource-Aware Job Placement Code Understanding Dataset
---

# Resource-Aware Job Placement Code Understanding Dataset

This dataset presents source-code understanding examples drawn from distributed task and job schedulers, covering resource checks, candidate-node filtering, constraint matching, and job placement logic. Each example pairs code with an analysis question and an explanatory answer about selection conditions, the impact of resource state, and the resulting placement decision. It supports training and evaluation of models that need to understand and explain resource-aware scheduling behavior.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | The scheduler source-code snippet to analyze, including relevant resource checks, node filtering, constraints, or placement logic. |
| placement_result | string | The resulting job placement behavior, including the selected node or the source-supported reason placement cannot proceed. |
| analysis_question | string | The question or instruction specifying which resource-aware scheduling behavior should be explained. |
| selection_conditions | string | An explanation, grounded in the supplied source code, of the conditions used to select or reject candidate nodes or jobs. |
| reasoning_explanation | string | A coherent explanation connecting the relevant code paths, selection conditions, resource state, and placement result. |
| resource_state_impact | string | An explanation of how available, requested, reserved, or otherwise tracked resources affect the scheduling decision. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

