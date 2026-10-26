---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: GPON Topology Fault Localization Reasoning Dataset
---

# GPON Topology Fault Localization Reasoning Dataset

This dataset covers PON ports, splitter hierarchies, ONT assignments, and topology relationships in GPON access networks, alongside text describing fault symptoms, alarm combinations, affected scope, and suspected locations. Each sample links the topology and impact pattern to a likely fault domain, such as a shared link, a splitter branch, or an individual user side, and includes a step-by-step rationale and conclusion. It supports reasoning SFT, network alarm analysis, and fiber access troubleshooting.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | Concise fault-localization conclusion suitable as the response in a reasoning SFT sample. |
| reasoning | string | Step-by-step explanation connecting the topology, alarm evidence, and impact pattern to the inferred fault location. |
| affected_scope | string | Inferred extent of impact, such as multiple ONTs sharing a link, one splitter branch, or a single user. |
| fault_evidence | string | Raw text describing observed symptoms, alarms, or alarm combinations associated with the fault. |
| affected_ont_ids | array | ONT identifiers inferred to be affected by the fault. |
| topology_description | string | Raw text describing the PON port, splitter hierarchy, ONT assignments, and relevant topology relationships. |
| suspected_fault_domain | string | Inferred location category for the fault. |
| suspected_fault_location | string | Specific PON port, shared link, splitter, branch, drop fiber, or user-side location most likely associated with the fault. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

