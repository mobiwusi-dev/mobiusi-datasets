---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: License Grant Scope Evidence Retrieval Dataset
---

# License Grant Scope Evidence Retrieval Dataset

This dataset provides retrieval questions about licensed subject matter, permitted uses, territory, exclusivity, and use restrictions in license agreements, together with scope assessments and supporting contract passages. Evidence is associated with its location in the text and the scope dimensions it supports. The data supports training and evaluating models that retrieve, interpret, and locate license grant information in legal documents, with applications in contract review and legal knowledge retrieval.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| scope_assessment | object | An extracted answer describing relevant dimensions of the license grant. |
| evidence_passages | array | Contract passages supporting the scope assessment, with references to their locations and the scope dimensions they support. |
| retrieval_question | string | A question about the licensed subject matter, permitted use, territory, exclusivity, or use restrictions. |
| license_contract_text | string | The source license agreement text to search for information about the scope of the grant. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

