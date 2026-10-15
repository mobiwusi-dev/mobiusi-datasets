---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Licensing Contract Question Answering and Clause Analysis Dataset
---

# Patent Licensing Contract Question Answering and Clause Analysis Dataset

This dataset contains patent licensing contract texts and closed-domain questions about contract definitions, licensed patent scope, field restrictions, exclusivity, and commercialization terms. Topics include milestone payments, sales royalties, improvements, and infringement handling, with reference answers and structured annotations such as legal relations and contract terminology. It supports training and evaluation for legal question answering, contract information extraction, and domain-specific model fine-tuning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | A closed-domain question about the content of a patent licensing contract. |
| patent_scope | object | Licensed patents, technical subject matter, territory, and granted rights parsed from the contract. |
| contract_text | string | Original text of a patent licensing contract or a related contract clause. |
| answer_summary | string | The key conclusion of the question and answer, based on the contract text and reference answer. |
| exclusive_level | string | The type of license exclusivity, such as exclusive, sole, or non-exclusive. |
| legal_relations | array | Parties, actions, rights, obligations, and conditional relationships extracted from contract clauses. |
| question_intent | string | Classification of the contract topic asked about, such as license scope, exclusivity, payments, improvements, or infringement handling. |
| commercial_terms | object | Milestone payments, sales royalties, and their calculation and payment arrangements extracted from the contract. |
| reference_answer | string | The reference or annotated answer corresponding to the question. |
| field_restrictions | array | Restrictions in the contract on the fields of use, product areas, or business areas for the licensed patents. |
| contract_definitions | array | Specialized terms, definitions, and scopes of application extracted from the contract. |
| infringement_handling | object | Contract provisions on identifying and reporting third-party infringement, enforcement, litigation, and allocation of costs. |
| improvement_technology | object | Contract provisions defining improvements and specifying ownership, grant-back licenses, and notification obligations. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

