---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Korean Housing and Rental Document Understanding Dataset
---

# Korean Housing and Rental Document Understanding Dataset

This dataset provides structured JSON samples of Korean housing and rental documents, including property listings, move-in guides, maintenance fee notices, repair announcements, and simplified rental terms. Annotations capture fee breakdowns, living conditions, assigned responsibilities, prohibitions, action steps, key terms, and interpretation notes. It supports training and evaluating models that interpret everyday Korean documents, extract essential information, and explain practical housing rules.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| fee_items | array | Rent, deposit, maintenance fees, utilities, repair costs, and other charges mentioned in the document. |
| key_terms | array | Important Korean words and fixed expressions from housing and rental documents, with their meanings in Chinese. |
| action_steps | array | Steps for tenants, landlords, or property managers, such as giving notice, submitting requests, paying fees, confirming details, or arranging repairs. |
| document_type | string | The housing or rental document category identified from its primary content. |
| document_title | string | A Chinese title extracted from or summarized based on the original document. |
| source_document | string | The full original Korean text of a housing or rental document to be interpreted. |
| document_summary | string | A Chinese summary of the housing, fees, living rules, repair arrangements, or rental terms covered by the document. |
| prohibited_items | array | Actions, items, uses, and consequences that the document explicitly prohibits or restricts. |
| living_conditions | array | Conditions concerning eligibility, occupancy, facility use, pets, smoking, noise, and other aspects of daily living. |
| interpretation_notes | string | Additional notes on ambiguity, implied conditions, timing, responsibility boundaries, or matters that may need confirmation with the property manager. |
| responsibility_assignments | array | Responsibilities assigned to the landlord, tenant, property manager, or other parties for repairs, fees, facilities, and contract matters. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

