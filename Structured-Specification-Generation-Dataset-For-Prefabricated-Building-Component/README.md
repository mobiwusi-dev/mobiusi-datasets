---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Structured Specification Generation Dataset for Prefabricated Building Components
---

# Structured Specification Generation Dataset for Prefabricated Building Components

This dataset contains prompt-response examples that turn component descriptions, design requirements, fabrication documents, or user prompts into structured component specification records. Records may cover component categories such as wall panels, composite slabs, beams, and columns, along with dimensions, materials, connection methods, and identifiers. The examples support format-constrained generation and help distinguish information stated in source materials from information that is missing. Use cases include information extraction, standardized component management, and supervised fine-tuning or evaluation of structured-output models for prefabricated construction.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| material | object | The materials used in the component, including any provided grades, designations, or applicable standards. Unprovided subfields may be left unspecified. |
| connection | object | Information about connections between components or between a component and the primary structure. Unprovided subfields may be left unspecified. |
| dimensions | object | The main geometric dimensions of the component. Dimensions not provided in the source materials may be left unspecified. |
| source_prompt | string | The original component description, design requirement, fabrication document content, or user prompt used to generate the component specification record. |
| component_category | string | The category of the component, such as a wall panel, composite slab, beam, or column. |
| information_status | object | Indicates which information is provided in the record and which information is missing, helping distinguish source facts from unavailable details. |
| component_identifier | string | The component number, model, or other identifying information provided in the source materials. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

