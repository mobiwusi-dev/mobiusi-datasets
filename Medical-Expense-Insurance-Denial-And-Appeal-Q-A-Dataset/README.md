---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Medical Expense Insurance Denial and Appeal Q&A Dataset
---

# Medical Expense Insurance Denial and Appeal Q&A Dataset

This dataset covers common reasons for denied medical expense insurance claims, review and appeal procedures, required submission materials, and applicable deadlines, with answers grounded in policy terms and claims-process documents. Each example can include a question, source material, a supported answer, the denial reason, action steps, required materials, deadlines, and citations, making it suitable for building and evaluating traceable insurance Q&A systems. It is designed to support rule retrieval and evidence-based open-book answering in retrieval-augmented generation workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct answer supported by the provided source material. |
| question | string | The user's question about a denied medical insurance claim or its review or appeal process. |
| citations | array | References identifying the source passages that support the answer and related instructions. |
| appeal_steps | array | The ordered actions a claimant should take to request a review or appeal the denial. |
| denial_reason | string | The reason for denial addressed by the question and answer, as stated or supported by the source material. |
| source_material | string | Policy terms, claims-process content, or relevant excerpts used as evidence for the answer. |
| appeal_deadlines | array | Applicable time limits and the events or conditions that determine when they apply. |
| required_materials | array | Documents or information identified by the source material as necessary for a review or appeal. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

