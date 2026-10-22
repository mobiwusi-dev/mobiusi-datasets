---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Claims and Technology Coverage Question Answering Dataset
---

# Patent Claims and Technology Coverage Question Answering Dataset

This dataset contains closed-domain questions about whether specific technology elements are covered by patents in a portfolio, using patent claims, specifications, and technical topics as context. Answers connect coverage assessments to relevant patent text, identify supporting claims or specification material, and may explain the rationale, limitations, or gaps. It is designed for patent portfolio management, technology coverage analysis, and supervised fine-tuning of domain-specific question-answering models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_text | string | A concise response explaining whether and how patents in the corpus cover the queried technology element. |
| patent_corpus | string | Source text containing patent identifiers, claims, and specification material for the portfolio being assessed. |
| coverage_status | string | The overall assessment of how the patents in the corpus cover the technology element. |
| patent_evidence | array | Patent-specific citations and excerpts supporting the coverage assessment. |
| coverage_rationale | string | Reasoning that connects the queried technology element to relevant patent text, including applicable limitations or gaps. |
| technology_question | string | The question identifying a technology element whose coverage in the patent corpus must be assessed. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

