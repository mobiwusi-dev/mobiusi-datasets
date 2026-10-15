---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial Litigation Confidentiality and Privilege Document Understanding Evaluation Dataset
---

# Commercial Litigation Confidentiality and Privilege Document Understanding Evaluation Dataset

This dataset focuses on protective orders, privilege logs, sealing motions, confidentiality designation challenges, and related court rulings in commercial litigation. It captures key elements such as protected information categories, grounds for protection, disclosure restrictions, dispute scope, and case outcomes through source documents and structured semantic annotations. It supports evaluation of legal document understanding, model validation for domain-specific applications, and the development of legal information extraction workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| dispute_scope | array | The scope of disputes between the parties concerning confidentiality, privilege, document categories, specific pages, or particular information. |
| document_type | string | The type of document, such as a protective order, privilege log, sealing motion, confidentiality designation challenge, or court ruling. |
| protection_bases | array | Legal, factual, or commercial grounds asserted for restricting disclosure, sealing materials, or withholding them from filing. |
| parties_and_roles | array | Parties, counsel, third parties, and document providers mentioned in the document, along with their roles in the confidentiality or privilege dispute. |
| disclosure_outcome | string | The final disclosure status reflected in the document, such as nondisclosure, limited disclosure, delayed disclosure, public filing, or further review pending. |
| asserted_privileges | array | Evidentiary privileges or related protections asserted in the document. |
| key_supporting_spans | array | Key sentences, passages, or quotations from the source text that support the semantic annotations. |
| source_document_text | string | Original text or searchable text representation of a protective order, privilege log, sealing motion, confidentiality designation challenge, or related ruling. |
| court_treatment_result | string | The court's or adjudicating body's disposition of a confidentiality, privilege, sealing, or disclosure request, such as granting, denying, or partially granting it, requiring further explanation, or ordering resubmission. |
| case_procedural_context | string | A summary of the litigation stage and the procedural background giving rise to the relevant motion or dispute. |
| court_reasoning_summary | string | A summary of the main reasons for finding protection applicable or inapplicable, limiting disclosure, or making a procedural decision. |
| disclosure_restrictions | array | Restrictions at issue or imposed on disclosure recipients, methods, permitted uses, or access conditions. |
| material_subject_matter | string | A summary of the commercial or litigation topics addressed by materials, information, or evidence claimed to be confidential or privileged. |
| sealing_or_redaction_scope | array | The specific materials covered by a sealing or redaction request or order, including materials to be redacted, obscured, or left public. |
| confidentiality_designations | array | Confidentiality levels, labels, or party-applied designations appearing in the document. |
| conditions_or_follow_up_actions | array | Additional measures or follow-up actions required by the court to maintain protection, permit disclosure, or advance the proceedings. |
| protected_information_categories | array | Categories of information claimed or determined to be protected by confidentiality or privilege. |
| privilege_or_confidentiality_upheld | boolean | Whether the relevant confidentiality or privilege claim was ultimately upheld by the court or reflected as supported in the document. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

