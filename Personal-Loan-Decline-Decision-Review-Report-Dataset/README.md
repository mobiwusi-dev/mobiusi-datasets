---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Personal Loan Decline Decision Review Report Dataset
---

# Personal Loan Decline Decision Review Report Dataset

This dataset focuses on reviews of personal loan decline decisions, organizing application materials, decision records, applicable policies, prior review materials, and case summaries. It includes structured decline reasons, evidence mappings, policy analysis, review findings, dispositions, and complete internal reports. Its case-level, long-form examples trace the analysis from source materials to review conclusions, supporting domain-specific SFT for models that synthesize decision grounds and evidence into clear internal reports for consumer lending review, compliance checks, and report generation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_summary | string | A concise summary of the application, decline decision, and review scope. |
| denial_reasons | array | A structured explanation of each material reason supporting the decline decision. |
| policy_analysis | string | Analysis of how cited policies apply to the evidence and the original decline decision. |
| review_findings | array | Review results, including confirmation, qualification, or identification of errors and evidence gaps. |
| evidence_mappings | array | Traceable links between source evidence, policy provisions, and review conclusions. |
| review_disposition | string | The overall review outcome, stated with appropriate qualifications. |
| application_materials | string | Original application information and supporting materials relevant to the loan request. |
| final_internal_report | string | The complete internal report explaining decline reasons, evidence relationships, policy grounds, and review findings. |
| prior_review_material | string | Existing review notes, supplemental evidence, or correspondence relevant to the case. |
| policy_source_material | string | Applicable lending policies, decision criteria, and guidance provided as source material. |
| decline_decision_record | string | The original decision record, including the decline outcome and recorded reasons. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

