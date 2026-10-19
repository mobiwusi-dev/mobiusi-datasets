---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Air Cargo Claims and Liability Clause Evidence Retrieval Dataset
---

# Air Cargo Claims and Liability Clause Evidence Retrieval Dataset

This dataset organizes transport terms, claim guidance, and liability rules from express air cargo webpages into citable evidence passages for questions about cargo damage, loss, declared value, and claim deadlines. Records include source pages, retrieval queries, evidence text, clause references, and structured liability information; coverage depends on the webpages included. It supports the development and evaluation of retrieval-augmented generation systems for clause evidence retrieval, grounding, and claims question answering.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_url | string | URL of the webpage containing relevant air cargo transport terms or claims guidance. |
| evidence_text | string | A passage located and extracted from the source webpage that directly supports the retrieval query. |
| answer_summary | string | A concise answer to the retrieval query based on the evidence passage and consistent with the original clause. |
| claim_deadline | string | A deadline stated in the evidence for filing a claim, notifying of loss, or submitting an objection; marked as unspecified when not addressed. |
| issue_category | string | The topic covered by the evidence, such as cargo damage, cargo loss, declared value, liability limits, or claim deadlines. |
| liability_rule | string | A summary of the carrier's liability scope, liability limits, exclusions, or compensation rules based on the evidence passage. |
| retrieval_query | string | A query about cargo damage, loss, declaration, claim deadlines, or liability rules. |
| clause_reference | string | The clause number, section heading, or another identifier for locating the evidence passage on the webpage; marked as not identified when no clear reference is available. |
| source_page_content | string | Original HTML content from the source webpage, provided as the source for transport terms and claims rules. |
| declaration_requirement | string | Requirements in the evidence for declaring cargo value, reporting loss, or submitting claim documents; marked as unspecified when not addressed. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

