---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pediatric Febrile Neutropenia Care Pathway Constraint Evaluation Dataset
---

# Pediatric Febrile Neutropenia Care Pathway Constraint Evaluation Dataset

This evaluation dataset represents pediatric febrile neutropenia cases in JSON, recording fever and blood count information, risk stratification rationale, comorbidities, allergy history, and proposed management pathways, alongside applicable pathway rules and expected conflict points. It supports checks of whether risk classification, treatment plans, investigation requirements, and disposition comply with pathway constraints, as well as model evaluation and error analysis in pediatric hematology and oncology. It is intended for research and evaluation and should not replace clinical judgment or current care guidelines.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_record | object | Original JSON input containing the patient's clinical facts, proposed care, applicable pathway rules, and expected conflicts. |
| risk_validation | object | Computed assessment of whether the recorded risk category is supported by the clinical inputs and pathway rules. |
| overall_validation | object | Final computed benchmark outcome and concise summary of pathway consistency. |
| management_validation | object | Computed checks of proposed treatment, allergy compatibility, required investigations, and disposition. |
| pathway_conflict_analysis | object | Computed comparison of observed pathway discrepancies with the benchmark's expected conflict points. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

