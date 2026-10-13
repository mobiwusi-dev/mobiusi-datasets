---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Community Screening Eligibility and Follow-Up Constraint Verification Dataset
---

# Community Screening Eligibility and Follow-Up Constraint Verification Dataset

This dataset organizes community medicine screening program rules, recipient information, and post-screening disposition records in JSON, alongside derived validation results for eligibility, screening pathways, and follow-up or referral deadlines. Its examples cover key checks from inclusion criteria through overall constraint assessment, supporting evaluation of a model's ability to reason across multiple rules and detect inconsistencies. It is suitable for community screening quality control, medical rule validation, and domain-specific model evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| follow_up_record | object | Source record of screening completion, results, disposition, and follow-up or referral dates. |
| service_recipient | object | Source information about the person receiving community screening services. |
| pathway_validation | object | Derived comparison of the recorded disposition with the screening pathway specified by the program. |
| deadline_validation | object | Derived checks of follow-up or referral timing against the applicable program constraints. |
| eligibility_assessment | object | Derived assessment of whether the recipient meets the program's inclusion and exclusion criteria. |
| screening_program_rules | object | Source rules for the screening program, including eligibility criteria, pathway steps, and follow-up deadlines. |
| overall_constraint_result | object | Derived overall result combining eligibility, pathway, and timing validations. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

