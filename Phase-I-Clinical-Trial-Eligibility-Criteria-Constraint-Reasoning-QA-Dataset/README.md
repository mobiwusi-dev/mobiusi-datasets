---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Phase I Clinical Trial Eligibility Criteria Constraint Reasoning QA Dataset
---

# Phase I Clinical Trial Eligibility Criteria Constraint Reasoning QA Dataset

This dataset contains question-answer examples that assess candidate eligibility against inclusion and exclusion criteria in Phase I clinical trial protocols, including exceptions and relevant definitions. Examples support criterion-by-criterion assessment, evidence citation, identification of missing information, and an overall conclusion grounded in the protocol text. It is designed for reasoning SFT and clinical research QA evaluation, and does not replace clinical judgment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | The question asking whether the candidate meets the protocol's eligibility requirements. |
| final_answer | string | A direct response to the eligibility question, limited to the protocol text and supplied candidate information, with uncertainty stated where applicable. |
| protocol_text | string | Source text containing the trial's inclusion and exclusion criteria, exceptions, and relevant definitions. |
| overall_status | string | The overall protocol-based conclusion after considering applicable criteria and unresolved information. |
| reasoning_summary | string | A concise explanation of how criterion-level results, exceptions, and missing information determine the overall status. |
| missing_information | array | Information needed to resolve eligibility that is not present in the supplied candidate profile. |
| criterion_assessments | array | Assessment of each applicable inclusion or exclusion criterion, including evidence, exceptions, and unresolved information. |
| candidate_profile_json | string | Candidate information serialized as JSON, including relevant history, measurements, and other supplied facts. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

