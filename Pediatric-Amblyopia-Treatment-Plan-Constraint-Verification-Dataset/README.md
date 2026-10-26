---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Amblyopia Treatment Plan Constraint Verification Dataset
---

# Pediatric Amblyopia Treatment Plan Constraint Verification Dataset

This JSON dataset organizes pediatric amblyopia case and examination information alongside proposed treatment plans and follow-up schedules, with constraint checks and expected violation labels tied to case-specific requirements. It covers plan applicability, internal consistency, and follow-up adequacy, enabling evaluation of whether models can detect mismatches between a plan and case conditions or identify insufficient monitoring arrangements. It is suited to domain-specific model evaluation, decision-support system validation, and research on clinical plan review workflows; the dataset description does not specify a record count.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_information | object | Original patient and examination information used to assess the proposed management plan. |
| constraint_checks | array | Derived checks of whether the proposed plan satisfies case-specific clinical and follow-up constraints. |
| evaluation_summary | string | Concise derived summary of plan applicability, consistency, and follow-up adequacy. |
| follow_up_adequacy | string | Derived assessment of whether the proposed follow-up interval and monitoring satisfy the case-specific follow-up requirements. |
| plan_consistency_status | string | Derived overall assessment of whether the proposed plan is internally consistent with the case information. |
| proposed_management_plan | object | Original proposed treatments, prescriptions, and monitoring arrangements to be evaluated against the case information. |
| expected_violation_labels | array | Derived labels identifying the expected constraint violations in the proposed plan. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

