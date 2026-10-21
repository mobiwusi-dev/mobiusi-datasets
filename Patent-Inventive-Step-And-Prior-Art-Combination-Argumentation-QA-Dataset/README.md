---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Inventive-Step and Prior-Art Combination Argumentation QA Dataset
---

# Patent Inventive-Step and Prior-Art Combination Argumentation QA Dataset

This dataset provides question-and-answer examples for assessing the inventive step of patent claims, including arguments involving combinations of multiple prior-art references, differences in technical features, and relevant technical teachings. Each example contains a question, the claim under review, supplied prior-art evidence, and a reasoned answer that links key arguments to the cited documents and passages. It supports patent invalidity analysis, evidence-grounded reasoning, and training or evaluation of domain-specific QA models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A reasoned answer that identifies material feature differences, explains whether and why the prior-art references could be combined, discusses relevant technical teachings or motivation, and links each material argument to the supplied documents and passages rather than stating only a conclusion. |
| question | string | The question to answer about the patent claim, including any requested obviousness assessment. |
| patent_claim | string | The patent claim or relevant claim limitations being assessed for obviousness. |
| prior_art_evidence | string | The supplied prior-art documents or excerpts, with document identifiers and relevant passages preserved so arguments can cite the closed evidence set. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

