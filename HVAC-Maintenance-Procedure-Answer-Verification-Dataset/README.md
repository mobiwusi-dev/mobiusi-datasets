---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: HVAC Maintenance Procedure Answer Verification Dataset
---

# HVAC Maintenance Procedure Answer Verification Dataset

Designed for evaluating maintenance question answering for industrial HVAC equipment, this dataset records maintenance questions, candidate action steps, and structured procedure references covering step order, prerequisites, and safety restrictions. It also provides step-by-step mappings, missing requirements, safety violations, completeness scores, and overall assessments. These records support automated evaluation of answer completeness, procedural compliance, and safety, as well as system improvement and benchmarking.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| overall_pass | boolean | Indicates whether the answer is complete and complies with the procedure and applicable safety restrictions. |
| candidate_steps | array | The proposed maintenance action steps, recorded in the order given in the answer under evaluation. |
| procedure_basis | object | The procedure steps, prerequisites, and safety restrictions used to verify the answer. |
| safety_violations | array | Safety restrictions that the answer under evaluation violates or may violate. |
| completeness_score | number | Measures how fully the answer covers applicable procedure requirements, on a scale from 0 to 1. |
| evaluation_details | array | Records how each candidate action step corresponds to procedure requirements and explains the evaluation rationale. |
| overall_assessment | string | Summarizes answer completeness, procedural compliance, and reasons for any failure. |
| maintenance_question | string | The industrial HVAC equipment maintenance question to be answered. |
| missing_required_steps | array | Procedure steps or other required elements not covered by the answer under evaluation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

