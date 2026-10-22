---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mobile Application Penetration Test Finding Triage and Remediation QA Dataset
---

# Mobile Application Penetration Test Finding Triage and Remediation QA Dataset

This dataset provides long-form expert question-and-answer examples based on mobile application penetration test reports, vulnerability evidence, affected components, and conflicting or incomplete findings. It covers finding triage, root cause analysis, impact and exploitability assessment, evidence uncertainty, severity rationale, and remediation recommendations for domain-specific supervised fine-tuning and capability evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| task_prompt | string | The original question or instruction requesting finding triage and remediation analysis. |
| case_summary | string | A concise overview of the application context, reported issue, and key facts relevant to the assessment. |
| impact_scope | string | The affected application components, data, users, platforms, or environments, and the likely consequences of exploitation. |
| expert_answer | string | The complete user-facing response integrating triage, root cause, scope, exploitability, evidence limitations, severity, and remediation. |
| finding_triage | string | A normalized interpretation of the finding that reconciles conflicting claims and separates confirmed facts from assumptions. |
| severity_rationale | string | A reasoned severity assessment based on exploitability and impact, avoiding unsupported precision when source information is incomplete. |
| assessment_material | string | The source penetration test report, finding descriptions, vulnerability evidence, and available details about affected components. |
| root_cause_analysis | string | The most likely technical root cause, reasoned from the supplied report and evidence, with material uncertainty noted. |
| evidence_and_uncertainty | string | An assessment of evidence quality and consistency, missing information, and further validation that could resolve material uncertainty. |
| exploitability_assessment | string | The prerequisites, attacker capabilities, access conditions, and evidence-supported limitations relevant to exploiting the issue. |
| remediation_recommendations | string | Prioritized corrective actions addressing the root cause, with practical implementation guidance and verification steps where applicable. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

