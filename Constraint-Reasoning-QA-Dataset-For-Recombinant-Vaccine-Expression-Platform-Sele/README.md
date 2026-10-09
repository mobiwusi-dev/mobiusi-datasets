---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Constraint-Reasoning QA Dataset for Recombinant Vaccine Expression Platform Selection
---

# Constraint-Reasoning QA Dataset for Recombinant Vaccine Expression Platform Selection

This scenario-based question-answer dataset focuses on selecting expression platforms for recombinant vaccine antigens. Its scenarios combine constraints involving target protein properties, processing and folding requirements, production scale, and process limitations, with records covering platform assessments, overall decisions, reasoning, and missing information. It supports supervised fine-tuning and evaluation of constraint reasoning, as well as prototyping decision-support tools for vaccine research and production.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question_text | string | The original question describing the target protein properties, processing or folding requirements, production scale, process limitations, and other relevant constraints. |
| decision_status | string | The conclusion supported by the stated constraints, such as one recommended platform, multiple feasible platforms, no platform meeting the constraints, or insufficient information. |
| answer_rationale | string | A summary of how the stated constraints support the selection or exclusion of expression platforms and the overall conclusion. |
| missing_information | array | Key details that could affect platform selection but are absent from the question; an empty array indicates that no relevant information is missing. |
| platform_assessments | array | A platform-by-platform record of whether each candidate satisfies the stated constraints, with supporting reasons. |
| insufficient_information | boolean | Indicates whether the question lacks enough information to reach a definite platform-selection conclusion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

