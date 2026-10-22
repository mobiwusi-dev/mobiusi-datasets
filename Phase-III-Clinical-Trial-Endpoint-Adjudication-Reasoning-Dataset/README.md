---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Phase III Clinical Trial Endpoint Adjudication Reasoning Dataset
---

# Phase III Clinical Trial Endpoint Adjudication Reasoning Dataset

This dataset provides question-and-answer examples for endpoint adjudication in Phase III clinical trials, constructed from event definitions, decision criteria, and case materials in trial protocols or endpoint charters. It covers endpoint standards, relevant case facts, adjudication outcomes, step-by-step rationales, and supporting evidence, enabling models to assess whether an event meets a stated endpoint definition. Organized as text-based Q&A, it is suited to clinical rule reasoning and reasoning SFT; the delivered manifest specifies the available sample count and scope.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | The question asking whether the event satisfies the endpoint definition, or requesting a related judgment under the stated criteria. |
| reasoning | string | A step-by-step explanation applying the stated criteria to the relevant facts in the case materials. |
| case_material | string | The clinical case information relevant to deciding whether the event meets the endpoint criteria. |
| endpoint_definition | string | The endpoint definition, event criteria, and adjudication rules drawn from the trial protocol or endpoint charter. |
| supporting_evidence | string | The specific case facts and endpoint criteria that support the adjudication outcome. |
| adjudication_outcome | string | The conclusion on whether the event meets the endpoint definition, using a clear outcome such as yes, no, or indeterminate. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

