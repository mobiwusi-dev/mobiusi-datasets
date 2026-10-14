---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cache Invalidation Propagation and Dependency Reasoning Dataset
---

# Cache Invalidation Propagation and Dependency Reasoning Dataset

This dataset contains supervised source code examples covering cache writes, updates, deletions, invalidation notifications, and replica synchronization. The examples focus on changed entities, dependency relationships, affected cache scope, invalidation conditions, notification channels and consumers, synchronization timing, and potential dirty-data paths. It supports code reasoning, cache consistency analysis, and evaluation for distributed systems development.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reasoning | string | Detailed justification based on source code control flow, call relationships, and dependency propagation. |
| final_label | object | The cache consistency reasoning conclusion used for training and evaluation. |
| source_code | string | A source code snippet containing cache write, update, deletion, invalidation, notification propagation, or replica synchronization logic. |
| impact_summary | string | A summary of the overall impact of the write, update, or deletion on caches, notification flows, and replica synchronization scope. |
| operation_type | string | The primary data operation identified from the source code. |
| changed_entities | array | The data entities, tables, keyspaces, or sets of cache objects directly modified or deleted by the operation. |
| dependency_graph | array | The dependencies and propagation directions among changed entities, cache entries, notification topics, and replicas. |
| dirty_data_paths | array | The complete paths from a data change to dirty data in caches or replicas, with associated risk analysis. |
| invalidation_assessment | object | An assessment of whether cache invalidation is triggered, its triggering conditions, and the affected cache key scope. |
| replica_sync_assessment | object | An analysis of whether the change triggers replica synchronization, its targets, and inconsistency risks caused by synchronization timing. |
| notification_propagation | object | An analysis of whether invalidation or data-change notifications are emitted, which channels carry them, and which consumers process them. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

