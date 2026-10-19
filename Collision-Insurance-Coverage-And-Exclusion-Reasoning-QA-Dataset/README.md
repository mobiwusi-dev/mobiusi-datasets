---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Collision Insurance Coverage and Exclusion Reasoning QA Dataset
---

# Collision Insurance Coverage and Exclusion Reasoning QA Dataset

This dataset presents question-and-answer examples for assessing vehicle collision insurance claims, combining policy terms, vehicle and coverage information, accident facts, and specific questions. The examples connect key evidence about coverage activation, the policy definition of a collision, and applicable exclusions to determine whether a loss is covered. Each example includes a determination, reasoning, supporting evidence, and a concise answer, making the dataset suitable for reasoning SFT, evaluation, and claims analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | Concise response to the question, consistent with the final coverage determination and supporting evidence. |
| question | string | The user question asking whether the described loss falls within collision coverage. |
| reasoning | string | Step-by-step explanation linking coverage status, the collision definition, accident facts, and exclusions to the final determination. |
| policy_terms | string | Source text containing relevant coverage conditions, collision definitions, and exclusions. |
| accident_facts | string | Source text describing the incident, the circumstances of the collision, and the resulting loss. |
| evidence_basis | string | Relevant policy language and accident details that support the reasoning and final determination. |
| exclusion_status | string | Assessment of whether a relevant policy exclusion applies to the loss. |
| coverage_determination | string | Final determination of whether the specific loss is covered under collision coverage, based on policy conditions, the collision definition, and applicable exclusions. |
| coverage_activation_status | string | Assessment of whether the relevant collision coverage was in effect for the vehicle at the time of the incident. |
| collision_definition_status | string | Assessment of whether the accident facts meet the policy's definition of a collision. |
| vehicle_coverage_information | string | Source text describing the insured vehicle and relevant coverage details, such as policy status and effective dates. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

