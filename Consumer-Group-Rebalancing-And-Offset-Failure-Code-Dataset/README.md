---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Consumer Group Rebalancing and Offset Failure Code Dataset
---

# Consumer Group Rebalancing and Offset Failure Code Dataset

This dataset contains source code examples covering consumer group coordination, partition assignment, rebalancing, and offset commits, with annotations for defects that may cause duplicate consumption, message loss, or invalid state. Structured fields describe bug categories, code locations, triggering scenarios, affected components, runtime risks, and expected behavior, supporting code-path verification, fault localization, and regression test design. It is intended for code quality analysis and reliability improvement in distributed messaging and event streaming platforms.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| severity | string | The estimated impact level of the bug on message processing and consumer group correctness. |
| root_cause | string | The underlying logic error or coordination flaw that causes the observed issue. |
| source_code | string | The input source code sample containing consumer group or offset-handling logic. |
| bug_category | string | The primary category of the identified bug, such as duplicate consumption, message loss, or invalid state. |
| bug_location | string | The function, code region, or relevant line range where the issue occurs. |
| observed_risk | string | The likely runtime consequence, such as repeated processing, skipped messages, or inconsistent group state. |
| failure_scenario | string | The sequence of events or group state changes that can trigger the bug. |
| expected_behavior | string | The correct behavior the relevant code path should maintain during coordination, rebalancing, or offset commits. |
| validation_checks | array | Suggested checks or test conditions for verifying the affected code path and confirming the bug or its resolution. |
| affected_components | array | The consumer group or offset management components affected by the issue. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

