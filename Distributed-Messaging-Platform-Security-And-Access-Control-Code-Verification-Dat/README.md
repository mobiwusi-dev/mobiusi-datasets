---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Distributed Messaging Platform Security and Access Control Code Verification Dataset
---

# Distributed Messaging Platform Security and Access Control Code Verification Dataset

This dataset contains source code from distributed messaging and event-streaming platforms, focusing on authentication, authorization, access control, and request handling, with context for the platform and security scenario. It provides validation conclusions, issue categories, supporting evidence, and root-cause localization information for security-control logic. Use it to train and evaluate models for secure code review, access-control verification, defect investigation, and root-cause analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence | array | Relevant code excerpts, control-flow observations, or request conditions that support the analysis. |
| confidence | number | Confidence in the derived security assessment, expressed as a value from 0 to 1. |
| source_code | string | Source code under review, including the relevant security-control and request-handling logic. |
| task_context | string | Platform, component, and security scenario context needed to interpret the source code. |
| issue_category | string | Primary category of an identified issue, such as authentication bypass, authorization error, or improper access control. |
| validation_analysis | string | Reasoning that supports or challenges the reference conclusion, with attention to the applicable security boundary. |
| reference_validation | string | Dataset-provided conclusion on whether the security control contains a logic or boundary error. |
| remediation_guidance | string | Suggested changes to correct a defect while preserving intended authentication, authorization, or access-control behavior. |
| security_issue_found | boolean | Indicates whether analysis of the source code identifies a security-control defect. |
| root_cause_localization | string | Analysis identifying the code location and logic responsible for a security failure, or confirming the reference target. |
| security_control_summary | string | Concise summary of the relevant security-control logic and how it handles the request. |
| reference_root_cause_target | string | Dataset-provided root-cause location, such as a file path, function, or line range. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

