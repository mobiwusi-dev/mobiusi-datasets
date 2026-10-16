---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Korean Workplace Document Understanding Dataset
---

# Korean Workplace Document Understanding Dataset

Designed for Korean for Business learning and document understanding, this resource contains JSON-structured samples of common workplace materials, including emails, meeting notices, schedules, internal process guides, leave policies, and handover documents. Annotations cover document categories and topics, tasks and assignees, deadlines, request intent, priority, execution conditions, and implied collaboration relationships, supporting models that identify key information and action requirements in workplace communication. Check the product page for the exact sample count, field format, and licensing terms.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| priority | string | The overall handling priority inferred from the wording, deadlines, and business impact. |
| conditions | array | Conditions, prerequisites, and restrictions that affect task execution, leave requests, scheduling, or process applicability. |
| deadline_info | object | A structured representation of deadlines, time ranges, and recurring requirements mentioned in the document. |
| task_subjects | array | Tasks and action items identified in the document, including their responsible parties. |
| request_intent | string | The main action, confirmation, response, or information the author expects from the recipient. |
| source_document | object | The Korean workplace document to analyze, along with basic source information. |
| document_subject | string | A summary of the document's main topic or communication matter. |
| document_category | string | The workplace document category identified from its content. |
| collaboration_relations | array | Relationships among people, teams, or departments inferred from task assignment, approval, notification, handover, and feedback requirements. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

