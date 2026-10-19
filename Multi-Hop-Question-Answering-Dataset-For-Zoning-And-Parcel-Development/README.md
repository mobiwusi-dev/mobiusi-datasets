---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Multi-Hop Question Answering Dataset for Zoning and Parcel Development
---

# Multi-Hop Question Answering Dataset for Zoning and Parcel Development

This dataset focuses on parcel development decisions in housing and community planning, pairing parcel descriptions and zoning rules with development proposals, questions, conclusions, and reasoning. Its examples cover permitted uses, density limits, coverage requirements, and overlay zoning, requiring models to connect multiple conditions to assess compliance and identify applicable constraints or missing information. It supports planning-rule reasoning, supervised fine-tuning for question answering, and development proposal compliance evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise response to the question, including whether the development is permitted and its main restrictions. |
| question | string | The original question asking for an assessment based on parcel information and zoning rules. |
| reasoning | string | A logically ordered explanation connecting parcel conditions, permitted uses, density or coverage limits, and overlay zoning rules to reach the conclusion. |
| zoning_rules | string | Source text describing permitted uses, density limits, coverage requirements, overlay zoning, and related rules. |
| compliance_status | string | Assessment of whether the proposal complies with applicable rules; marked as requiring more information when details are insufficient. |
| parcel_description | string | Source information about the parcel's location, area, current condition, or other details relevant to planning decisions. |
| development_proposal | string | Source details of the proposed project's use, scale, building density, coverage, and related characteristics. |
| applicable_constraints | string | A summary of key restrictions, conditions, or information that must be verified for the proposed development. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

