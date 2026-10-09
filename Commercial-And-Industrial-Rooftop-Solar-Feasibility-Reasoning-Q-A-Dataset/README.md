---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial and Industrial Rooftop Solar Feasibility Reasoning Q&A Dataset
---

# Commercial and Industrial Rooftop Solar Feasibility Reasoning Q&A Dataset

This dataset organizes text-based project information for commercial and industrial rooftop solar installations, including usable roof area, electricity load profiles, structural limitations, shading, and grid-connection conditions. Its question-and-answer samples cover project context, feasibility questions, verdicts, key constraints, and evidence-based reasoning answers, making the basis for each assessment easier to trace. It is designed for reasoning SFT, training solar project decision analysis, and developing or evaluating models for commercial and industrial distributed solar planning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | Asks whether a solar project is feasible under the stated conditions or requests an analysis of its limitations. |
| key_constraints | string | Identifies roof, load, structural, shading, or grid-connection conditions that materially affect project feasibility. |
| project_context | string | Describes usable roof area, electricity load profile, structural limitations, shading, grid-connection conditions, and other relevant project information. |
| reasoning_answer | string | Provides a final response and a reasoned analysis grounded in the project context and constraints. |
| feasibility_verdict | string | States the assessment reached after considering the project constraints. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

