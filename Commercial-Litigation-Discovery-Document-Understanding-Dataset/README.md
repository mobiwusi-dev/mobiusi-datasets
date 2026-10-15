---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial Litigation Discovery Document Understanding Dataset
---

# Commercial Litigation Discovery Document Understanding Dataset

This dataset covers commercial litigation discovery documents, including interrogatories, requests for production, requests for admission, responses, objections, and supplemental responses. It focuses on analyzing the scope of requests, response positions, grounds for objections, reservations, and disputed issues, with fields for extracting item-level details and case context. It supports legal document analysis, legal technology development, and domain-specific evaluation of document understanding and information extraction models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| objections | array | Individual objections extracted from the document, including their scope, legal grounds, and effect on the response. |
| case_context | object | Case background extracted from the document, including the case name, jurisdiction, parties, and discovery stage. |
| reservations | array | Reservations made by the responding party concerning further searches, supplemental responses, changes in position, privilege claims, or other rights. |
| document_type | string | The discovery document type identified from the source text. |
| discovery_items | array | Discovery items separated by request or number, with the scope of each request and its corresponding response, objections, and reservations. |
| disputed_issues | array | Unresolved discovery issues identified in the document that may lead to negotiation, motion practice, or a court ruling. |
| document_summary | string | A summary of the document's request scope, overall response position, principal objections, reservations, and disputed issues. |
| raw_document_text | string | The source text of a discovery document to be analyzed, which may contain requests, responses, objections, reservations, and supplemental responses. |
| supplemental_response | object | Whether the document provides supplemental, amended, or corrected responses, and what has changed from prior responses. |
| overall_response_position | string | The responding party's overall position on the discovery requests, based on the full document. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

