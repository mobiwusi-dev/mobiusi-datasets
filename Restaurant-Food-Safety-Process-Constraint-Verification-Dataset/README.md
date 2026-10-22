---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Restaurant Food Safety Process Constraint Verification Dataset
---

# Restaurant Food Safety Process Constraint Verification Dataset

This dataset focuses on food-handling workflows in casual dining restaurants, covering receiving, storage, preparation, cooking, and hot holding. Each example includes a task prompt, a step-by-step proposed plan, explicit constraints extracted from the prompt, per-step assessments, and an overall compliance result, with checks for requirements such as time, temperature, separation, and sequence. It supports training and evaluating process verifiers that identify violations of stated rules without assuming regulatory thresholds for any particular region.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| task_prompt | string | The original text prompt, including any explicitly stated time, temperature, separation, or sequencing rules. |
| proposed_plan | string | The original step-by-step food-handling plan to be checked against the task prompt. |
| overall_result | string | The overall compliance outcome for the proposed plan, based only on the constraints explicitly provided in the task prompt. |
| step_assessments | array | Per-step evaluations of whether the proposed actions comply with the applicable explicit constraints. |
| extracted_constraints | array | The explicit constraints extracted from the task prompt for use in evaluating the proposed plan. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

