---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: SAT Problem Solving and Data Analysis Question Answering Dataset
---

# SAT Problem Solving and Data Analysis Question Answering Dataset

Built from SAT preparation web content, this dataset provides closed-domain question answering on ratios, percentages, statistics, probability, tables, and data interpretation. It covers terminology, conditions for applying concepts, data relationships, and common misconceptions. Records can include source content, questions, standard answers, explanations, key concepts, and structured analysis for training and evaluating SAT-focused knowledge assistants.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An accurate, closed-domain answer to the question. |
| question | string | An SAT data analysis question about ratios, percentages, statistics, probability, tables, or data interpretation. |
| explanation | string | Explains the reasoning, calculation basis, and use of the question data to determine the answer. |
| source_content | string | Original SAT preparation web content or a relevant excerpt used to generate the question and answer. |
| knowledge_point | string | Summarizes the main SAT data analysis concept or term tested, such as ratios, percentages, mean, median, or probability. |
| structured_analysis | object | Organizes the methods, conditions, data relationships, and common misconceptions involved in the question and answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

