---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Zoning and Land-Use Regulation Fact Verification Dataset
---

# Zoning and Land-Use Regulation Fact Verification Dataset

This dataset covers zoning provisions, permitted uses, development restrictions, and density rules in housing and community planning. Each record pairs a claim to be verified with relevant regulatory, planning, or web text, and includes a verdict, evidence excerpt, rationale, rule category, and provision reference. It supports model training and evaluation for planning information retrieval, regulatory question answering, and development rule checks.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| verdict | string | The assessment of the claim based on the supplied regulatory or planning text. |
| reasoning | string | An explanation of how the evidence supports or refutes the claim, or why it is insufficient to determine the claim. |
| claim_text | string | The specific claim about zoning, land use, development restrictions, or density rules that requires verification. |
| rule_category | string | The category of planning rule addressed by the claim. |
| regulation_text | string | The source text from a regulation, planning document, or webpage used to verify the claim. |
| evidence_excerpt | string | A passage from the regulatory or planning text that is directly relevant to the verdict. |
| provision_reference | string | The relevant provision number, section title, or other location information extracted from the source text; left blank when the text provides none. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

