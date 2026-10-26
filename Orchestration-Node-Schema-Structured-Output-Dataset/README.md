---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Orchestration Node Schema Structured Output Dataset
---

# Orchestration Node Schema Structured Output Dataset

Designed for input-output contracts in nodes used by LLM application orchestration platforms, this dataset pairs natural-language instructions, field definitions, or structural constraints with compliant structured responses. It covers common forms such as objects, arrays, nested fields, and optional fields. The data supports structured-output supervised fine-tuning, helping models generate schema-compliant results that orchestration nodes can consume while improving format adherence and structural generation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| instruction | string | The natural-language prompt specifying the required output format, fields, constraints, and optionality. |
| structured_output | object | The JSON object or array that follows the instruction and can be consumed by the orchestration node. Its schema may include nested or optional fields. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

