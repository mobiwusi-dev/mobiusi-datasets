---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Melasma Clinical Management Evidence Retrieval Dataset
---

# Melasma Clinical Management Evidence Retrieval Dataset

This dataset is built around clinical records concerning melasma and covers lesion distribution, potential triggers, pregnancy and hormone-related context, photoprotection, topical treatment history, and recurrence. Each record organizes related management questions and safety considerations, along with evidence domains and queries for searching medical literature or guidelines, helping models connect individual clinical contexts with evidence on treatment, safety, and recurrence management. It supports dermatology evidence retrieval, clinical question formulation, and domain-specific model training and evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| clinical_record | string | Original text documenting the patient's melasma-related symptoms, medical history, treatment course, and follow-up information. |
| trigger_factors | array | Factors identified from the clinical record that may trigger or worsen melasma, such as sun exposure, heat exposure, pregnancy, hormonal changes, or medication. |
| evidence_domains | array | Categories of evidence topics relevant to the management questions for the current case. |
| recurrence_status | object | Information on prior melasma recurrence, recurrence frequency, time since the most recent recurrence, and related triggers. |
| lesion_distribution | object | An organized account of lesion locations, symmetry, distribution patterns, and affected areas based on the clinical record. |
| management_questions | array | Questions derived from the individual clinical record that require evidence support, such as treatment selection, comparative effectiveness, pregnancy safety, photoprotection, or recurrence prevention. |
| safety_considerations | array | Safety concerns identified from pregnancy, hormone exposure, prior adverse reactions, and treatment history. |
| photoprotection_history | object | Information on sunscreen use, sun-protective measures, frequency of use, and adherence. |
| pregnancy_hormone_context | object | Information on pregnancy, pregnancy plans, oral contraceptives, hormone therapy, and other hormone-related exposures, organized to support safety evidence retrieval. |
| topical_treatment_history | array | Past or current topical therapies used for melasma management, including agents, ingredients, treatment duration, outcomes, and adverse reactions. |
| evidence_retrieval_queries | array | Chinese or English queries generated from the patient's circumstances for searching medical literature or guidelines. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

