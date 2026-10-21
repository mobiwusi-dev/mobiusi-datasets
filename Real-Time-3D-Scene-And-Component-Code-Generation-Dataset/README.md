---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Real-Time 3D Scene and Component Code Generation Dataset
---

# Real-Time 3D Scene and Component Code Generation Dataset

This dataset pairs natural-language scene requests with corresponding code for real-time 3D engines, covering scene structure, entity definitions, component attachment, and property initialization. The examples support training models to translate scene descriptions into engine code for tasks such as scene graph construction and component configuration. It is suitable for code supervised fine-tuning, engine development assistance, and model capability evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| task_type | string | Primary code-generation task represented by the request, such as scene graph construction, component attachment, or property initialization. |
| engine_name | string | Name of the real-time 3D simulation engine targeted by the generated code, when specified or identifiable from the request. |
| request_text | string | Natural-language instructions describing the scene structure, entities, components, and desired configuration. |
| generated_code | string | Engine code that constructs the requested scene, attaches components, and initializes their properties. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

