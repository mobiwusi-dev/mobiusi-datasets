---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Indoor DAS RF Link Budget Constraint QA Dataset
---

# Indoor DAS RF Link Budget Constraint QA Dataset

This dataset covers RF link components in indoor distributed antenna systems, including signal sources, feeders, splitters, couplers, and antennas. Examples provide conditions such as loss, gain, power, and limits, paired with questions and answers that calculate link budgets or assess constraint compliance. Records include relevant numeric results and reasoning, supporting engineering design assistance and the training and evaluation of RF constraint reasoning models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reasoning | string | Concise explanation of the calculation and how the result compares with the applicable constraints. |
| answer_text | string | Answer to the question, including the relevant link budget calculation or constraint assessment. |
| feasibility | boolean | Whether the link budget satisfies the explicitly stated RF constraints. |
| source_text | string | Original text containing the indoor DAS link components, RF values or limits, and the question to answer. |
| calculated_value | number | Numeric result derived from the stated RF conditions, such as received power or total path loss. |
| calculated_value_unit | string | Unit for the calculated value, such as dBm or dB. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

