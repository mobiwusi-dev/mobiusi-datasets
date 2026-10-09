---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Air Express Customs Clearance Tool Selection Dataset
---

# Air Express Customs Clearance Tool Selection Dataset

This dataset focuses on international air express customs clearance workflows, pairing business inputs such as shipment details, declaration context, user requests, and available tools with the tools selected by the model and their call parameters. Scenarios cover clearance document verification, declaration information lookup, and clearance status handling. The examples support tool-use SFT and evaluation for models that select appropriate documentation, declaration, or status-handling tools in cross-border express workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| tool_call | object | The tool selected by the model based on the business input, together with its call parameters. |
| input_context | object | Original business input, including the user request, shipment and declaration information, and available tools. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

