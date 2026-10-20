---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Road Traffic Accident Rescue Legal Case Document Understanding Dataset
---

# Road Traffic Accident Rescue Legal Case Document Understanding Dataset

This dataset focuses on judgments and related legal handling documents concerning road traffic accident rescue. It pairs source documents with structured information on case profiles, parties, disputed issues, rescue responsibilities, legal grounds, reasoning, and outcomes. Evidence excerpts support verification of key conclusions, making the data suitable for legal document understanding and domain-specific supervised fine-tuning. It can support training and evaluation for legal information extraction, case summarization, and rescue responsibility analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| parties | array | Parties involved in the accident, rescue, or legal proceedings, together with their procedural or handling roles. |
| legal_basis | array | Legal rules cited or substantively applied in the document and their relationship to the disputed issues. |
| case_profile | object | Case type, court, case number, judgment date, and other information identified from the source document. |
| case_summary | string | A consolidated summary of the case background, rescue-related disputes, responsibility analysis, and final outcome. |
| court_reasoning | string | Main reasoning used by the court or handling body to establish facts, allocate rescue responsibilities, and address disputed issues. |
| disputed_issues | array | Road traffic accident rescue disputes explicitly discussed in the document and the positions of the parties. |
| handling_result | object | The judgment ruling or legal handling decision, including liability findings, cost allocation, and procedural outcome. |
| evidence_references | array | Document excerpts and locations supporting key facts, responsibility findings, or handling conclusions, enabling verification of the structured analysis. |
| source_document_text | string | Full text of a judgment or legal handling document related to road traffic accident rescue. |
| rescue_responsibilities | array | Rescue-related duties after the accident, such as providing assistance, giving notice, cooperating, or advancing costs, and whether those duties were fulfilled. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

