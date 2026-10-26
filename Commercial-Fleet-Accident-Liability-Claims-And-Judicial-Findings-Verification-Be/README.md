---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial Fleet Accident Liability Claims and Judicial Findings Verification Benchmark
---

# Commercial Fleet Accident Liability Claims and Judicial Findings Verification Benchmark

Designed for commercial fleet accident disputes, this benchmark covers legal documents such as complaints, answers, motions, court orders, verdicts, and judgments. It labels relevant passages as party allegations, procedural records, or judicial findings, and evaluates whether each document supports a specific liability proposition at the level asserted. It is suited to training and evaluating legal-document verifiers and to reviewing liability information in commercial fleet insurance claims.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| court_name | string | The name of the court identified in the document, if available. |
| party_names | string | The names of the parties referenced in the document, separated by semicolons. |
| document_date | string | The date shown on or associated with the source document, in YYYY-MM-DD format when available. |
| document_type | string | The kind of legal document, such as a complaint, answer, motion, court order, verdict, or judgment. |
| accident_summary | string | A concise summary of the fleet accident circumstances described in the document, without treating disputed statements as established facts. |
| responsible_party | string | The party identified as responsible by the relevant judicial finding, or an explicit indication that responsibility is not established. |
| procedural_posture | string | A concise description of the procedural stage or event reflected in the document. |
| support_assessment | string | Whether the cited document supports the target liability proposition at the level asserted. |
| source_document_text | string | The full text of the commercial fleet accident legal document being evaluated. |
| verification_rationale | string | A concise explanation linking the document language and its procedural or evidentiary status to the support assessment. |
| judicial_finding_status | string | Whether the target proposition was expressly determined by the court or remains an allegation, procedural matter, or unresolved issue. |
| proposition_source_class | string | The status of the document passage most relevant to the target proposition. |
| relevant_document_excerpt | string | A verbatim excerpt that is relevant to the target liability proposition and its evidentiary status. |
| allegation_conflation_error | boolean | Whether the target proposition incorrectly presents a party allegation as an established or judicially found fact. |
| target_liability_proposition | string | The specific statement about fault, negligence, responsibility, or liability that the verifier must assess. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

