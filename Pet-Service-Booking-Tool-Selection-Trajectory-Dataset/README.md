---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Pet Service Booking Tool Selection Trajectory Dataset
---

# Pet Service Booking Tool Selection Trajectory Dataset

This dataset captures interaction trajectories from users requesting pet services through booking completion, covering service search, retrieval of pet and service details, availability checks, and booking submission. Records show how tool choices and call sequences vary by request, alongside the original trace, structured booking details, tool-call sequence, and booking result. It is designed for building and evaluating tool-use models for pet service booking, especially supervised fine-tuning (SFT).

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| tool_calls | array | Tool calls recorded in the order they occurred, including service search, information retrieval, availability checks, and booking submission. |
| pet_profile | object | Pet information extracted from the interaction or tool results. |
| source_trace | string | The original record of the user's request and tool-call process, stored as JSON text. |
| user_request | string | The pet service booking request extracted from the original interaction. |
| booking_result | object | The status and confirmed booking details recorded after booking submission. |
| service_request | object | The requested service and time preferences compiled from the user's request and service search results. |
| trajectory_summary | string | A text summary of the tool choices and call sequence for the booking. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

