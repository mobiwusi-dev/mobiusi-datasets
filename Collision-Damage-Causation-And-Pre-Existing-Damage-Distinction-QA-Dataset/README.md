---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Collision Damage Causation and Pre-Existing Damage Distinction QA Dataset
---

# Collision Damage Causation and Pre-Existing Damage Distinction QA Dataset

Designed for collision insurance claim assessment, this question-answer dataset combines accident narratives, prior claim and repair records, inspection findings, and claim notes to determine whether disputed damage resulted from the current collision. Each example can include a causation decision, a concise explanation, and an ordered evidence chain, helping models integrate information across sources and explain their reasoning. It supports reasoning SFT and evaluation of damage attribution in vehicle claims.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_notes | string | Adjuster or insurer notes relevant to the disputed damage and the claim investigation. |
| evidence_chain | array | Ordered evidence links showing how source observations support or weaken the causation conclusion. |
| accident_narrative | string | Text describing the circumstances, timing, and mechanics of the reported collision. |
| prior_claim_records | string | Text of relevant prior claims, damage reports, and repair history for the vehicle. |
| assessment_conclusion | string | Concise answer explaining the causation determination and any important qualifications. |
| causation_determination | string | Categorical conclusion on whether the disputed damage is attributable to the current collision. |
| disputed_damage_question | string | The question identifying the disputed damage and asking whether it is attributable to the current collision. |
| repair_inspection_descriptions | string | Text describing inspection findings, observed damage, repairs, and any assessments of damage age or condition. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

