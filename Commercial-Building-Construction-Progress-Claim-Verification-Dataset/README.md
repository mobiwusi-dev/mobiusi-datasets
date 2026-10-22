---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial Building Construction Progress Claim Verification Dataset
---

# Commercial Building Construction Progress Claim Verification Dataset

This dataset covers text records such as daily and weekly construction reports, progress narratives, and planned milestones, alongside claims about work completion or schedule variance that require verification. Examples are organized around time windows, work status, planned dates, and conflicting evidence across reports, supporting model judgments on whether a claim is supported, contradicted, or indeterminable from the records. Its structured evidence and verdict fields help train construction progress verification and project report review systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| candidate_claim | string | Source candidate statement about work completion, work status, or schedule variance to be verified. |
| progress_reports | string | Source daily reports, weekly reports, and progress narratives used as evidence. |
| claim_time_window | string | Normalized date or time period referenced by the candidate claim, when identifiable. |
| planned_milestones | string | Source schedule milestones, target dates, and planned completion details relevant to the claim. |
| claimed_work_status | string | Normalized description of the work activity and completion status asserted by the candidate claim. |
| supporting_evidence | string | Relevant excerpts or concise references from source records that support the candidate claim. |
| verification_verdict | string | Assessment of whether the candidate claim is supported, contradicted, or indeterminable from the available records. |
| contradicting_evidence | string | Relevant excerpts or concise references from source records that conflict with the candidate claim, including disagreements between reports. |
| schedule_variance_days | integer | Computed day difference between the reported or claimed completion date and the applicable planned milestone date; positive values indicate lateness and negative values indicate early completion. |
| verification_rationale | string | Concise explanation linking report dates, work status, milestone timing, and conflicting evidence to the verdict. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

