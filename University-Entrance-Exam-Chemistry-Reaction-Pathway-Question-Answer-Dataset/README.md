---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: University Entrance Exam Chemistry Reaction Pathway Question-Answer Dataset
---

# University Entrance Exam Chemistry Reaction Pathway Question-Answer Dataset

This dataset contains university entrance exam chemistry questions paired with reasoning-based answers. Using clues such as substance properties, reaction conditions, and experimental observations, each sample guides a model through inferring reaction relationships and reaching a conclusion. Records include the source problem, ordered reasoning steps, a reaction pathway, and the final answer, supporting chemistry multi-hop reasoning training, exam question solving, and model evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_answer | string | The concise conclusion that answers the original chemistry question. |
| source_problem | string | The original exam question, including any provided substance properties, reaction conditions, and experimental observations. |
| reasoning_steps | array | An ordered sequence of concise inference steps used to solve the chemistry problem. |
| reaction_pathway | array | The ordered sequence of substances and reaction relationships inferred from the problem. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

