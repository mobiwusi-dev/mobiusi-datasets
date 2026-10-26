---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Virtual Laboratory Simulation Model Principles and Assumptions QA Dataset
---

# Virtual Laboratory Simulation Model Principles and Assumptions QA Dataset

This dataset organizes knowledge-based question answering about virtual laboratory simulation models using platform or experiment documentation as source material. It covers model principles, applicability, assumptions, and known limitations, with source excerpts and character offsets to make supporting evidence traceable. It supports domain-specific supervised fine-tuning and helps models explain the settings and boundaries within which simulation results apply.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence | array | Source excerpts and character offsets supporting the answer and its claims about the model. |
| answer_text | string | Direct answer grounded in the supplied source material. |
| assumptions | array | Explicit assumptions used to construct or interpret the simulation model. |
| limitations | array | Known restrictions, omitted effects, or caveats that constrain interpretation of simulation results. |
| source_text | string | Original platform or experiment documentation used as the evidence source. |
| question_text | string | Question about the simulation model, its assumptions, applicability, or limitations. |
| model_principle | string | Explanation of the governing principle or simulated mechanism, when stated in the source. |
| applicability_scope | string | Conditions, systems, or scenarios for which the simulation results are intended to apply. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

