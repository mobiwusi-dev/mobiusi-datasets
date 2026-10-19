---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: University Entrance Exam Physics Multi-Step Reasoning Q&A Dataset
---

# University Entrance Exam Physics Multi-Step Reasoning Q&A Dataset

This dataset provides question-and-answer text for university entrance exam physics problems, including the original question, key physical quantities and constraints, ordered reasoning steps, and the final answer. It focuses on solving problems through multiple steps, from extracting information in the prompt to connecting physical laws and completing calculations or judgments. Use it for reasoning fine-tuning of physics QA models, solution-skills evaluation, and intelligent education applications.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| final_answer | string | The final answer, including units or a concise explanation when appropriate. |
| question_text | string | The original exam question, including any stated conditions, values, and constraints. |
| reasoning_steps | array | Ordered solution steps that connect relevant physical laws and calculations to the result. |
| extracted_quantities | array | Physical quantities, values, units, and constraints identified from the question. Represent each entry as a concise text string. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

