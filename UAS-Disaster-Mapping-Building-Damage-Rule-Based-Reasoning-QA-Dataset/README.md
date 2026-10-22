---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: UAS Disaster Mapping Building Damage Rule-Based Reasoning QA Dataset
---

# UAS Disaster Mapping Building Damage Rule-Based Reasoning QA Dataset

This dataset pairs textual descriptions of building conditions documented in unmanned aerial surveys with explicit damage assessment rules to create questions about damage classification and evidence sufficiency. It covers cases where the evidence supports a rule-based category as well as cases where the available information is insufficient for a determination, helping models connect observations to professional criteria. It is suited to post-disaster building assessment, emergency mapping analysis, and training or evaluation of rule-grounded reasoning models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | Question asking for a damage classification or whether the available evidence is sufficient to determine one. |
| reasoning | string | Explanation linking the observed evidence to the applicable rule, including why evidence is insufficient when no category can be determined. |
| damage_rules | string | Explicit criteria for mapping observed building conditions to damage categories. |
| final_answer | string | Concise answer to the question, stating the inferred damage category or that it cannot be determined from the available evidence. |
| damage_category | string | Damage category inferred by applying the stated rules, or an explicit indication that the category cannot be determined. |
| building_observations | string | Textual description of visible building conditions documented by unmanned aerial survey. |
| classification_status | string | Indicates whether the provided evidence and rules support a damage classification. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

