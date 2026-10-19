---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Comprehensive Chromatography Instrument Troubleshooting QA Dataset
---

# Comprehensive Chromatography Instrument Troubleshooting QA Dataset

This long-form question-answering dataset covers chromatography instrument malfunctions, including operating symptoms, error messages, and reference information from manuals and technical documents. Each sample calls for evidence-based synthesis and provides a diagnostic summary, likely causes, an ordered troubleshooting process, recommended actions, and notes on uncertainty, supporting the training and evaluation of models for professional fault analysis. It emphasizes links between evidence and conclusions rather than treating a single error code as a definitive diagnosis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| likely_causes | array | Potential causes listed by likelihood or impact. Do not equate a single error code with a definitive conclusion. |
| evidence_basis | array | The symptoms, error messages, or technical material supporting the diagnosis and proposed checks, with links between evidence and conclusions. |
| case_description | string | The original problem input, including instrument operating anomalies, observed symptoms, error messages, and the user's question. |
| diagnosis_summary | string | A concise overview of the likely fault condition based on the symptoms, error messages, and reference materials. |
| uncertainty_notes | string | Missing information, conditions that affect the diagnosis, and points that still need verification. If uncertainty is limited, state the scope supported by the available evidence. |
| recommended_actions | array | Suggested actions after troubleshooting. Clearly recommend qualified service personnel when professional repair or safety risks are involved. |
| technical_materials | string | Original reference materials, such as instrument manuals, technical documents, or fault-related text. Use an empty string when no materials are available. |
| troubleshooting_steps | array | Actionable checks listed in a recommended order, progressing from simple, low-risk checks to more in-depth investigation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

