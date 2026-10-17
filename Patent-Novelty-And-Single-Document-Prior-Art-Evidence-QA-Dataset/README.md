---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Novelty and Single-Document Prior-Art Evidence QA Dataset
---

# Patent Novelty and Single-Document Prior-Art Evidence QA Dataset

This dataset presents novelty questions based on patent claims and a single prior-art document, with fields for claim text, source evidence, questions, conclusions, citations, and feature correspondence analysis. It focuses on whether one document discloses the relevant claimed features and requires answers to connect evidence to those features using only the supplied materials, while noting material differences or missing limitations. It supports domain-specific model fine-tuning and evaluation for patent invalidity analysis, evidence retrieval, and novelty assessment.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | The full text of the patent claim being assessed. |
| answer_text | string | A concise answer stating the conclusion and grounding it in the cited evidence and feature correspondence. |
| question_text | string | The novelty question asking whether the prior-art document discloses the relevant features of the claim. |
| cited_evidence | array | Specific passages from the prior-art document that support the assessment, with a locator and the claim feature addressed by each passage. |
| prior_art_text | string | The text of the single prior-art document used as the evidence source for the assessment. |
| anticipation_conclusion | string | The assessment of whether the single prior-art document discloses the claimed subject matter for novelty purposes. |
| correspondence_analysis | string | An explanation of how each cited passage corresponds to a claim feature, including material differences or missing limitations. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

