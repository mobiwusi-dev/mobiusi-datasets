---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Construction Submittal Evidence Verification Dataset
---

# Construction Submittal Evidence Verification Dataset

Covering material submittals, product data, and construction plans for commercial building projects, this dataset provides text excerpts from submittals and project requirements, along with candidate conclusions, support statuses, evidence, and reasoning. It is designed to train models to determine whether conclusions are grounded in the available text and to connect evidence with project requirements. Typical uses include construction document review, requirement verification, and evaluation of reasoning in the building sector.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| evidence | array | Specific excerpts or references supporting the assessment of the candidate answer. |
| reasoning | string | A concise explanation connecting the evidence and project requirements to the support status. |
| support_status | string | Assessment of whether the candidate answer is supported by the available excerpts. |
| candidate_answer | string | The claim or conclusion to verify against the submittal content and project requirements. |
| submittal_excerpt | string | Relevant text from a material submittal, product data sheet, or construction plan. |
| project_requirement_excerpt | string | Relevant text from project specifications, contract documents, or other applicable requirements. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

