---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lignite Mine Safety Procedure Constraint Verification Benchmark Dataset
---

# Lignite Mine Safety Procedure Constraint Verification Benchmark Dataset

Designed for safety procedures in open-pit lignite mines, this benchmark pairs scenario text specifying risk controls, work-permit conditions, and procedural requirements with candidate responses for evaluation. It provides constraint-compliance annotations for individual steps and identifies omitted controls, ordering errors, and conflicts. The data supports process-verifier training and evaluation, mine safety workflow review, and research on constraint adherence.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| safety_scenario | string | The source text describing an open-pit lignite mine scenario and its explicit safety, risk-control, and work-permit requirements. |
| omitted_controls | array | Explicit scenario controls or requirements that are missing from the candidate response. |
| step_annotations | array | Step-by-step evaluations of the candidate response against the explicit constraints extracted from the scenario. |
| overall_rationale | string | A concise explanation of the overall assessment, highlighting the most important omissions, ordering errors, or conflicts where applicable. |
| candidate_response | string | The source response containing the proposed work procedure or safety-related steps to be evaluated. |
| overall_assessment | string | The overall assessment of the candidate response's compliance with the explicit scenario constraints. |
| extracted_constraints | array | Structured constraints derived from the scenario, including risk controls, permit requirements, prohibitions, prerequisites, and required step ordering. |
| sequence_and_conflict_findings | array | Findings identifying incorrect step ordering or mutually incompatible steps in the candidate response. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

