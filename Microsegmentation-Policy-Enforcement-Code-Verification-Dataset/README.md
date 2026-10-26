---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Microsegmentation Policy Enforcement Code Verification Dataset
---

# Microsegmentation Policy Enforcement Code Verification Dataset

This dataset contains Python source code snippets from network microsegmentation enforcement components, along with verification claims about whether the code allows, denies, or isolates traffic as intended. Each sample provides code-path evidence and policy-boundary analysis to help models understand enforcement logic and assess whether implementation behavior matches the claim. It supports training and evaluation for microsegmentation policy review, security code analysis, and code verification.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | Python source text from the enforcement component to be reviewed. |
| claim_assessment | string | Indicates whether the code supports or contradicts the verification claim, or whether the available evidence is insufficient to decide. |
| code_path_evidence | array | Relevant code locations and branch conditions supporting the assessment. |
| decision_rationale | string | A concise explanation connecting the enforcement logic to the assessment of the claim. |
| verification_claim | string | The proposed judgment about whether the code allows, denies, or isolates traffic as intended. |
| isolation_boundary_analysis | string | Analysis of the policy boundary, including the affected traffic scope and whether the code preserves or violates the intended separation. |
| observed_enforcement_action | string | The traffic-handling action determined from the relevant code paths. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

