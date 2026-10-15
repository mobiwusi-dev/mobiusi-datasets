---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Infringement Pleadings Document Understanding Dataset
---

# Patent Infringement Pleadings Document Understanding Dataset

This dataset covers complaints, statements of defense, counterclaims, legal briefs, and other written submissions in patent infringement cases. Its structured content focuses on case and patent details, disputed facts, claim-by-claim infringement comparisons, party positions, defense arguments, evidence references, and cited legal authorities. It supports domain-specific training, information retrieval, legal analysis tool development, and evaluation of legal document understanding systems.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| legal_basis | array | Laws and judicial interpretations cited in the document, along with the legal propositions they support. |
| document_text | string | Full text of a pleading document in a patent infringement case. |
| document_type | string | Type of pleading document, such as a complaint, statement of defense, counterclaim, legal brief, or written opinion. |
| disputed_facts | object | Disputed content concerning the accused product or method, alleged acts, and related technical facts. |
| defense_reasons | array | Arguments raised by the defendant or other parties concerning infringement, patent validity, liability, or claimed damages. |
| party_positions | array | Facts, legal arguments, and requested relief raised by the plaintiff, defendant, or other participants, with relevant positions linked where available. |
| case_information | object | Basic case details and procedural information identified in the document. |
| document_summary | string | A concise synthesis of the case background, key disputes, party positions, and principal requests discussed in the document. |
| claim_comparisons | array | Comparisons by claim and technical feature recording the parties' positions on whether the accused solution falls within the scope of protection. |
| patent_information | object | Basic information about the patents and claims involved in the document. |
| evidence_references | array | Evidence cited in the document to support disputed facts or legal arguments. |
| counterclaim_information | object | Counterclaim facts, requested relief, and legal grounds extracted from counterclaims or related pleadings. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

