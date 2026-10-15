---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Legal Document Understanding Dataset for Trade Secret Misappropriation Cases
---

# Legal Document Understanding Dataset for Trade Secret Misappropriation Cases

This dataset covers pleadings, evidence review opinions, and judicial decisions in trade secret misappropriation cases, addressing issues such as secrecy, reasonable confidentiality measures, access, use or disclosure, causation, and damages. Its structured information includes document types, case parties, claims and defenses, evidence, element analysis, and judgments, supporting models that interpret fact-intensive IP dispute documents and connect evidence with legal elements.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_parties | array | Parties extracted from the document, including their litigation roles and positions. |
| document_text | string | Original text of a pleading, evidence review opinion, or judicial decision from a trade secret misappropriation case. |
| document_type | string | Document type identified from the text, such as a complaint, answer, evidence review opinion, judgment, or ruling. |
| evidence_items | array | Evidence materials, their stated purposes, and the parties' opinions on authenticity, relevance, and admissibility. |
| element_findings | array | Analysis connecting case facts and evidence to elements such as secrecy, confidentiality measures, access, use or disclosure, and causation. |
| damage_assessment | object | Structured representation of claimed losses, calculation bases, causation, and the compensation amount ultimately determined by the court. |
| claims_and_defenses | object | Structured representation of the rights holder's claims, the accused party's defenses, and the issues in dispute. |
| judgment_conclusion | object | Liability findings, judgment outcome, remedies, and reasoning extracted from a judicial decision. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

