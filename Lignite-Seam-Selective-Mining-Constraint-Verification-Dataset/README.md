---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lignite Seam Selective Mining Constraint Verification Dataset
---

# Lignite Seam Selective Mining Constraint Verification Dataset

Designed for process verification in lignite mining, this dataset covers seam boundaries, partings, selective mining requirements, and other mining quality constraints, together with candidate extraction steps and work instructions to review. Each step is paired with a verification result, supporting training and evaluation of models that detect violations of seam control, selective extraction, and coal-waste separation requirements. It is suitable for process verifier development, mining plan review, and research on extraction quality control.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| mining_constraints | string | Original descriptions of coal seam boundaries, partings, selective mining requirements, and other mining quality constraints. |
| step_verifications | array | Verification results for each candidate mining step, indicating whether it complies with the specified constraints. |
| candidate_mining_steps | string | Candidate extraction steps and work instructions to be checked against the mining constraints. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

