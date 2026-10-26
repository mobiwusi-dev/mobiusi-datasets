---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Contact Center Routing Constraint Extraction Dataset
---

# Contact Center Routing Constraint Extraction Dataset

This dataset pairs administrator instructions for routing calls or messages with structured target configurations, covering interaction channels, required skills, routing priority, business hours, applicability conditions, and fallback rules. It supports extracting routing constraints from configuration text to automate routing setup in contact center communication software. Use it for structured-output supervised fine-tuning, information extraction training, and model evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| priority | integer | The priority level explicitly required for the interaction or its routing rule. |
| business_hours | object | The schedule during which the routing constraint applies. |
| fallback_rules | array | Actions to take when the primary routing destination or handling path is unavailable or unsuccessful. |
| required_skills | array | Skills an agent or routing destination must have to handle the interaction. |
| instruction_text | string | The original administrator instruction describing how calls or messages should be routed. |
| interaction_channel | string | The interaction channel specified or implied by the instruction. |
| applicability_conditions | array | Conditions that determine which interactions are subject to the routing instruction. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

