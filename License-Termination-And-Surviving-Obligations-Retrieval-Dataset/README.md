---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: License Termination and Surviving Obligations Retrieval Dataset
---

# License Termination and Surviving Obligations Retrieval Dataset

This dataset focuses on termination and expiry provisions in license agreements and related legal documents, including breach triggers, cure periods, termination rights, notice procedures, and effective dates. It also organizes post-termination restrictions on sales, inventory disposition, return or destruction of materials, confidentiality, and other surviving obligations, with supporting quotations, evidence locations, and retrieval summaries. It is designed to build or evaluate legal RAG systems that retrieve evidence about when a licensing relationship ends and what responsibilities continue afterward.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_text | string | Original text of the license agreement, amendment, or related legal provision to be analyzed. |
| record_scope | string | Summarizes the agreement, clause, product, territory, parties, or licensing relationship covered by the evidence. |
| evidence_quote | string | Quotes key provisions that directly support an assessment of termination conditions, termination procedures, or post-termination obligations. |
| materials_return | string | Extracts requirements to return, delete, destroy, or stop using licensed materials, technical materials, samples, equipment, and related storage media after termination. |
| evidence_location | string | Records where key evidence appears in the source material, such as a page, section, clause number, paragraph heading, or text span. |
| parties_and_roles | string | Identifies the licensor, licensee, and other relevant parties, and describes their roles in termination or post-termination obligations. |
| retrieval_summary | string | Summarizes the relationships among termination conditions, notice procedures, post-termination sales restrictions, and surviving obligations in a format suited to retrieval and evaluation. |
| termination_right | string | Explains which party may terminate, rescind, or revoke the license under what conditions, along with any restrictions on exercising that right. |
| termination_triggers | array | Lists events that may terminate or rescind the licensing relationship, such as material breach, insolvency, expiry, or other agreed events. |
| breach_and_cure_terms | string | Extracts breach conduct, breach notices, cure periods, methods of cure, and consequences if the breach is not cured. |
| inventory_disposition | string | Extracts requirements for selling, repurchasing, destroying, transferring, or otherwise disposing of existing inventory, work in progress, or manufactured products after termination. |
| license_term_or_expiry | string | Extracts the license term, renewal conditions, expiry date, and rules on whether expiry automatically terminates the license. |
| confidentiality_survival | string | States whether confidentiality obligations continue after termination or expiry, how long they survive, and which confidential information they cover. |
| other_surviving_obligations | array | Lists other obligations that remain in effect after termination or expiry, such as intellectual property ownership, indemnification, audits, payments, dispute resolution, or governing law obligations. |
| termination_effective_timing | string | Describes when termination or rescission takes effect, including upon notice delivery, expiry of a cure period, the expiry date, or another specified condition. |
| termination_notice_requirement | string | Extracts who must issue a termination notice, its required form and delivery method, advance notice period, recipient, and other procedural requirements. |
| post_termination_sales_restriction | string | Extracts requirements to stop manufacturing, selling, distributing, promoting, or licensing related products and services after termination, including the applicable period. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

