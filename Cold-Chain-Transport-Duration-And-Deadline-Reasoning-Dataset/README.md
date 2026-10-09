---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cold-Chain Transport Duration and Deadline Reasoning Dataset
---

# Cold-Chain Transport Duration and Deadline Reasoning Dataset

Designed for refrigerated trucking scenarios, this dataset records transport events in chronological order, delivery deadlines or time windows, and the evaluation time used for assessment. It provides supervised answers for transport duration, remaining time, overdue status, and delivery status, together with concise calculation explanations to support learning temporal interval and deadline reasoning. It is suitable for reasoning SFT, temporal reasoning evaluation, and research on transport timeliness.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| is_overdue | boolean | For a delivered shipment, compares the delivery event time with the deadline. For a shipment not yet delivered, compares the evaluation time with the deadline. |
| event_sequence | array | Records transport events in chronological order. Event types should identify key milestones such as departure or delivery. |
| delivery_status | string | The delivery status inferred from the transport event sequence. |
| evaluation_time | string | The reference time used to calculate remaining time or determine whether an undelivered shipment is overdue, formatted as an ISO 8601 datetime. |
| delivery_constraint | object | Describes the applicable deadline or delivery time window for the transport. |
| remaining_time_minutes | number | The number of minutes from the evaluation time until the deadline or the end of the delivery window. A negative value indicates that the time limit has passed. |
| calculation_explanation | string | Briefly explains the event times and deadline used, along with the duration calculation and overdue assessment. |
| transport_duration_minutes | number | The number of minutes between the departure and delivery events in the transport event sequence. If a key event is missing, calculate the duration from the available events and explain the basis. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

