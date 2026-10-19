---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Vehicle Collision Coverage and Adjacent Coverage Boundary QA Dataset
---

# Vehicle Collision Coverage and Adjacent Coverage Boundary QA Dataset

This question-and-answer dataset presents vehicle collision coverage scenarios involving boundaries with adjacent protections such as comprehensive and liability coverage. Questions require analysis of the cause and circumstances of a loss, policy definitions, and exclusions to distinguish relevant clauses. It supports insurance policy QA, coverage boundary analysis, and training or evaluation of retrieval-augmented generation models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct response to the question grounded in the supplied facts and policy wording. |
| question | string | The question to be answered about the applicability or boundaries of collision coverage. |
| reasoning | string | An explanation connecting the cause and circumstances of the loss to applicable policy definitions and coverage provisions. |
| loss_scenario | string | A concise account of the loss event, including its cause and circumstances relevant to coverage analysis. |
| policy_context | string | Relevant policy definitions, insuring agreements, conditions, and exclusions extracted from the source document. |
| source_document | string | Original serialized input containing the coverage question, loss facts, and relevant policy wording or excerpts. |
| supporting_clauses | array | Relevant policy clauses that support or qualify the answer. |
| boundary_distinction | string | An explanation of how collision coverage differs from relevant adjacent protections, such as comprehensive or liability coverage, in the scenario. |
| coverage_determination | string | The reasoned conclusion on whether collision coverage applies to the described loss. |
| exclusions_and_limitations | array | Policy exclusions, conditions, or limitations that may affect the coverage determination. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

