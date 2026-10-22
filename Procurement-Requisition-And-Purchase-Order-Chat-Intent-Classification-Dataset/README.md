---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Procurement Requisition and Purchase Order Chat Intent Classification Dataset
---

# Procurement Requisition and Purchase Order Chat Intent Classification Dataset

This dataset contains chat requests for procurement requisitions and purchase orders, covering actions such as creating, modifying, approving, querying, and canceling documents, with an intent label for each request. Its fields include the original message, intent label, general action, procurement document type, and extracted entity mentions, supporting models that interpret procurement instructions and identify user needs. It is suited to chat interfaces in procurement and spend management software, enterprise purchasing automation, and request routing.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| action | string | The general operation requested by the user. |
| intent_label | string | The specific classified procurement intent expressed in the user message. |
| user_message | string | The original procurement request submitted by the user through chat. |
| document_type | string | The type of procurement document targeted by the request. |
| entity_mentions | array | Important values or references extracted from the request, such as a supplier, amount, date, or document reference. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

