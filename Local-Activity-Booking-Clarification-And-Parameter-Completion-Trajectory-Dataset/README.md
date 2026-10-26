---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Local Activity Booking Clarification and Parameter Completion Trajectory Dataset
---

# Local Activity Booking Clarification and Parameter Completion Trajectory Dataset

This dataset contains local activity booking requests with missing or ambiguous details, the clarification conversations needed to resolve them, and the resulting tool-use trajectories. Records cover parameter assessment, identification of unresolved details, question generation, and construction of booking arguments such as activity, date, and party size after the user provides more information. It supports training and evaluation of conversational systems that clarify incomplete requests and make accurate booking tool calls when sufficient information is available.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_record | object | The original booking request, clarification conversation, and observed tool trace provided as a single input record. |
| final_tool_call | object | The booking tool call and its arguments generated after incorporating available clarification responses. |
| parameter_assessment | object | The inferred status and known value of each parameter required to book the activity. |
| unresolved_parameters | array | The names of required booking parameters that are missing or ambiguous. |
| clarification_required | boolean | Indicates whether the assistant needs more information from the user before booking can proceed. |
| clarification_questions | array | Questions needed to resolve missing or ambiguous booking details. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

