---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Vaccine Clinical Trial Eligibility Criteria Logic Reasoning QA Dataset
---

# Vaccine Clinical Trial Eligibility Criteria Logic Reasoning QA Dataset

This dataset focuses on inclusion criteria, exclusion criteria, and applicable exceptions in vaccine clinical trial protocols. Each example pairs a protocol excerpt with relevant candidate facts and an eligibility question, then provides a criterion-by-criterion analysis, a decision, and its rationale. It is designed to train and evaluate rule-based reasoning about trial eligibility rather than simple recall of medical knowledge.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| protocol_excerpt | string | Source text containing the trial's inclusion criteria, exclusion criteria, and applicable exceptions. |
| candidate_profile | string | Facts about the candidate that are relevant to trial eligibility. |
| criterion_analysis | array | Ordered assessment of each applicable inclusion criterion, exclusion criterion, and exception, based only on the supplied protocol and candidate facts. |
| decision_rationale | string | Concise explanation of how the criterion assessments support the overall eligibility decision. |
| eligibility_decision | string | Overall eligibility conclusion derived from all applicable criteria and exceptions. |
| eligibility_question | string | Question asking whether the candidate meets the trial's eligibility requirements. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

