---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Claim Interpretation Judicial Decisions Dataset
---

# Patent Claim Interpretation Judicial Decisions Dataset

This dataset focuses on judgments, rulings, and written judicial opinions involving the interpretation of patent claim terms. Its structured annotations cover terms requiring interpretation, interpretive sources, technical context, disagreements between parties, the court's adopted conclusions, and supporting evidence excerpts. It supports legal document understanding, patent dispute analysis, and domain-specific legal model training.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| target_terms | array | Claim terms identified in the judicial document that require interpretation, definition, or clarification by the court. |
| evidence_spans | array | Key passages extracted from the judicial document that support term interpretation, assessment of technical context, or the court's conclusion. |
| source_document | object | The original patent judgment, ruling, or written judicial opinion, together with basic case information. |
| technical_context | object | The technical setting and functional relationships of the terms, summarized from the patent specification, claims, and technical facts of the case. |
| interpretation_basis | array | Sources cited by the court or parties to interpret claim terms, including claim text, the specification, drawings, technical materials, prior art, and legal rules. |
| court_adopted_conclusion | object | The court's final interpretation of the relevant terms, the interpretive method and reasoning, and the resulting effect on claim scope. |
| party_interpretation_dispute | object | Different interpretations of claim term meanings and claim scope advanced by the plaintiff, defendant, patent holder, accused infringer, or other participants in the proceedings. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

