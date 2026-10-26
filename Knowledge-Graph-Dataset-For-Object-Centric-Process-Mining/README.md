---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Knowledge Graph Dataset for Object-Centric Process Mining
---

# Knowledge Graph Dataset for Object-Centric Process Mining

The dataset contains process event records, business objects such as orders, invoices, and deliveries, and the associations between events and objects. Its structured content covers source data, normalized events and objects, event-object links, and derived cross-object process relations. It supports analysis of events involving multiple objects and processes in which several objects participate together, as well as process knowledge graph and knowledge base construction.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| events | array | Normalized process events extracted from the source data. |
| raw_source_data | object | Original source records containing process events, business objects, and their associations. |
| business_objects | array | Normalized business objects, such as orders, invoices, and deliveries. |
| cross_object_relations | array | Derived process relations between business objects involved in related events or process steps. |
| event_object_associations | array | Links between process events and the business objects involved in them. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

