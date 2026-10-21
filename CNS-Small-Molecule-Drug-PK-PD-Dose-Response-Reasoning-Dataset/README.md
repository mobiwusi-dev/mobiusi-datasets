---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: CNS Small-Molecule Drug PK/PD Dose-Response Reasoning Dataset
---

# CNS Small-Molecule Drug PK/PD Dose-Response Reasoning Dataset

This question-and-answer text dataset covers doses or concentrations, receptor occupancy, time courses, and pharmacological observations for central nervous system small-molecule drugs. It focuses on analyzing dose-response relationships, distinguishing potency, efficacy, and drug exposure, and judging whether the available evidence supports a proposed pharmacological interpretation. It is designed for CNS pharmacology research, dose analysis, and training reasoning models for drug development.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| concise_answer | string | Direct answer grounded in the information provided in the source case text. |
| source_case_text | string | Original text describing the drug, dose or concentration, receptor occupancy, time course, pharmacological observations, and relevant context. |
| reasoning_question | string | Question about the dose-response relationship or interpretation of the pharmacological data reported in the case. |
| supporting_evidence | string | Brief identification of the reported dose, concentration, occupancy, time-course, or effect observations that support the answer. |
| evidence_support_judgment | string | Assessment of whether the supplied data support the proposed pharmacological explanation, including limits on the strength of that conclusion. |
| dose_response_interpretation | string | Interpretation of the relationships among dose or concentration, receptor occupancy, exposure over time, and observed pharmacological effects. |
| uncertainties_and_limitations | string | Important missing information, alternative interpretations, or methodological limitations affecting the dose-response conclusion. |
| potency_efficacy_exposure_distinction | string | Explanation of which observations relate to potency, maximal efficacy, or drug exposure, and whether these concepts can be distinguished from the supplied data. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

