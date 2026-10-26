---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Local Activity Booking Availability Query Tool-Use Trajectory Dataset
---

# Local Activity Booking Availability Query Tool-Use Trajectory Dataset

This dataset contains tool-use trajectories for checking bookable time slots in local activity booking scenarios. It covers user requests and conversation context, along with parameters such as activity and session identifiers, dates, time ranges, participant counts, and time zones. The data supports training models to extract and organize availability-query arguments from natural-language requests, as well as developing and evaluating function-calling capabilities for booking assistants.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| timezone | string | The time zone used to interpret the requested date and time range, preferably as an IANA time zone identifier. |
| tool_name | string | The name of the availability tool called for the query. |
| session_id | string | The identifier of the activity session or scheduled instance when the query targets a specific session. |
| activity_id | string | The identifier of the activity whose availability is queried, when provided or resolved. |
| activity_name | string | The name of the local activity whose availability is queried. |
| requested_date | string | The date for which the user wants to check bookable time slots, represented in ISO 8601 date format when available. |
| time_range_end | string | The end of the requested local-time range, represented in 24-hour HH:MM format when available. |
| time_range_start | string | The beginning of the requested local-time range, represented in 24-hour HH:MM format when available. |
| participant_count | integer | The number of people for whom availability is being checked. |
| user_request_context | string | The user's original request and relevant conversation context for formulating the availability query. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

