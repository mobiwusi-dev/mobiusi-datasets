---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial Litigation Motion Document Semantic Understanding Dataset
---

# Commercial Litigation Motion Document Semantic Understanding Dataset

This benchmark covers commercial litigation filings, including motions to dismiss, motions for summary judgment, motions to exclude evidence, and briefs supporting or opposing those motions. It organizes information on motion type and position, targets, applicable standards, argument chains, cited facts, legal authorities, and requested rulings. Use it to evaluate legal document understanding, argument extraction, and legal semantic analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| cited_facts | array | Specific facts used to support legal claims, rebut opposing arguments, or describe disputed issues. |
| motion_type | string | The primary procedural motion type addressed in the document. |
| raw_document | object | Original text of the commercial litigation motion document and its basic source information. |
| motion_target | object | The claims, causes of action, evidence, or other matters targeted by the motion. |
| argument_chain | array | Premises, reasoning, conclusions, and supporting facts organized in the order presented in the document. |
| legal_citations | array | Cases, statutes, rules, judicial interpretations, and other legal authorities cited in the document. |
| motion_position | string | The document's position on the motion, such as filing, supporting, opposing, or partially opposing it. |
| requested_ruling | object | The procedural or substantive ruling requested from the court. |
| applicable_standards | array | The legal rules, review standards, and burdens of proof cited and applied to the motion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

