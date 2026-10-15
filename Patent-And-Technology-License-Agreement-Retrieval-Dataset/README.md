---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent and Technology License Agreement Retrieval Dataset
---

# Patent and Technology License Agreement Retrieval Dataset

This dataset focuses on patent and technology license documents, covering key terms such as licensed patent scope, delivery of technical materials, field and territory restrictions, manufacturing and sales rights, improvements, infringement handling, export compliance, and financial terms. Its content supports clause-level retrieval and structured extraction, while source excerpts and locations help users verify search results. It is suitable for legal document RAG, technology commercialization license review, contract research, and legal knowledge base development.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| parties | array | The licensor, licensee, and other relevant entities identified in the document. |
| source_text | string | The original text of a patent or technology license agreement, serving as the sole raw input for structured extraction and retrieval. |
| improvements | object | Provisions on improvements to licensed technology, derivative technology, ownership of results, disclosure, and grant-back rights. |
| document_type | string | The document type identified from its content, such as a patent license agreement, technology license agreement, amendment, or technology transfer agreement. |
| export_control | object | A summary of obligations concerning the export or re-export of technology, products, and materials, as well as related trade compliance. |
| clause_evidence | array | Source clause excerpts and their locations supporting structured conclusions, for retrieval traceability and answer generation. |
| financial_terms | object | Extracted terms for license fees, milestone payments, sales royalties, reporting, audits, and payment timing. |
| key_obligations | array | Key party obligations extracted from the license document, including performance deadlines, triggering conditions, and consequences of breach. |
| licensed_rights | object | Extracted commercial rights, including rights to manufacture, use, sell, import, practice, and sublicense. |
| document_summary | string | A consolidated summary of the transaction background, core license arrangements, and principal restrictions in the document. |
| retrieval_keywords | array | Professional keywords generated from license terms to support RAG retrieval and semantic recall. |
| licensed_patent_scope | object | Identification and summary of the licensed patents, patent applications, and related technology. |
| manufacturing_sales_terms | object | A summary of terms governing licensed product manufacturing, quality, sales, marking, and commercialization commitments. |
| technical_material_delivery | object | A structured description of delivery arrangements for technical materials, drawings, samples, source files, and technical support. |
| infringement_and_enforcement | object | Extracted terms on identifying and notifying third-party infringement, litigation, cost allocation, and settlement control. |
| field_and_territory_restrictions | object | Restrictions on the permitted fields of use, territories, customers, channels, and exclusivity of the licensed technology. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

