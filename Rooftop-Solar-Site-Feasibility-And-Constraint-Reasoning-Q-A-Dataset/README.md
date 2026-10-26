---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Rooftop Solar Site Feasibility and Constraint Reasoning Q&A Dataset
---

# Rooftop Solar Site Feasibility and Constraint Reasoning Q&A Dataset

This dataset focuses on distributed rooftop solar site assessment, covering roof characteristics and usable areas, project limits, proposed equipment layouts, and explicit feasibility rules. Each question asks whether a plan satisfies all applicable constraints and identifies any violations with supporting evidence, providing structured examples from condition extraction and rule-by-rule checks to final conclusions. It supports rooftop solar plan assessment, constraint reasoning training, and evaluation of reasoning outputs.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | The direct response to the feasibility question, including the conclusion and any key failure reason. |
| question | string | The feasibility question extracted from the source case. |
| reasoning | string | A concise, evidence-based explanation of how the individual checks determine the overall feasibility result. |
| candidate_plan | string | A concise description of the proposed photovoltaic equipment layout or installation plan being evaluated. |
| project_limits | array | Project-specific restrictions or equipment placement limits stated in the case. |
| overall_feasible | boolean | Whether the candidate plan satisfies all applicable stated constraints. |
| source_case_text | string | The original case material containing roof conditions, project constraints, the proposed plan, explicit rules, and the question. |
| constraint_checks | array | Individual evaluations of the candidate plan against applicable conditions and rules. |
| feasibility_rules | array | Explicit rules used to determine whether the candidate plan is feasible. |
| roof_site_conditions | array | Relevant roof characteristics and usable-area conditions extracted from the source case. |
| unsatisfied_constraints | array | Conditions or rules that the candidate plan fails to satisfy; an empty array indicates that none are violated. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

