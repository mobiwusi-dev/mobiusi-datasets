---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Work-at-Height Safety Observation Hazard Information Extraction Dataset
---

# Work-at-Height Safety Observation Hazard Information Extraction Dataset

This dataset contains safety inspection and hazard observation records from work-at-height settings, paired with JSON annotations for work activities, hazard sources, exposed persons or entities, locations, and control measures explicitly mentioned in the records. The paired examples map field observations to structured information and can support training and evaluation of models that interpret safety records and extract information in a defined format. Typical uses include work-at-height safety inspections, hazard record organization, and development of structured-output models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| location | string | The worksite or location where the hazard is reported to occur. |
| hazard_source | string | A source of potential accidents or injuries mentioned in the record. |
| work_activity | string | The work activity or task mentioned in the record. |
| exposed_objects | array | People or other entities mentioned in the record as potentially affected by a hazard. |
| control_measures | array | Safety controls, corrective actions, or protective measures explicitly mentioned in the record. |
| observation_text | string | The original text of a safety inspection or hazard observation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

