---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Assembly Robot Grasp Stability Proof Verification Dataset
---

# Assembly Robot Grasp Stability Proof Verification Dataset

This dataset contains mathematical problems and candidate proofs concerning grasp stability in assembly robotics, covering contact definitions, force and moment balance equations, stability conditions, and force-closure criteria. Each example indicates whether the conclusion follows sufficiently from the stated conditions and includes a verification explanation and verdict summary, supporting model training and evaluation in mechanical proof reasoning. It is suited to robotic gripping, part manipulation, and grasp stability analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| proof_problem | string | The source mathematical statement, including contact definitions, force and moment balance equations, stability conditions, force-closure criteria, the proposed conclusion, and the candidate proof. |
| verdict_summary | string | A concise summary of the proof assessment, such as valid, invalid, or insufficiently justified. |
| conclusion_follows | boolean | Whether the candidate proof establishes that the conclusion follows sufficiently from the stated conditions. |
| verification_explanation | string | A mathematical explanation supporting the assessment, identifying the relevant conditions, inference steps, and any gaps or invalid reasoning. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

