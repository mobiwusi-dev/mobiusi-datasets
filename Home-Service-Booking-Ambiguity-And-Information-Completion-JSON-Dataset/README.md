---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Home Service Booking Ambiguity and Information Completion JSON Dataset
---

# Home Service Booking Ambiguity and Information Completion JSON Dataset

This dataset covers home service booking requests with missing, ambiguous, or conflicting details about timing, service scope, or the property, along with structured JSON outputs for handling them. Outputs include processing status, extracted details, missing fields, clarification questions, conflict records, and whether processing can proceed, with an emphasis on using only information stated in the request rather than inventing booking details. It is designed for structured-output supervised fine-tuning (SFT), JSON generation, information-gap detection, and evaluation of booking clarification workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| conflicts | array | Information in the request that is contradictory or cannot all be true at the same time. Use an empty array when there are no conflicts. |
| can_proceed | boolean | Whether there is enough information to continue processing the booking without further clarification from the user. |
| raw_request | string | The user's original home service booking request, provided as the source input for the record. |
| missing_fields | array | Information fields that are missing or need confirmation before the booking can be processed further. |
| extracted_details | object | Booking information explicitly stated or directly extractable from the original request. Use empty values for unknown or unstated details; do not invent information. |
| processing_status | string | The booking processing status based on the completeness and consistency of the request. |
| clarification_questions | array | Questions to ask the user about missing, ambiguous, or otherwise unconfirmed information. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

