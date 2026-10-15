---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Lease Default and Remedies Clause Retrieval Dataset
---

# Lease Default and Remedies Clause Retrieval Dataset

This dataset focuses on lease defaults such as nonpayment of rent, covenant breaches, bankruptcy, cure periods, acceleration, forfeiture, and damages. It pairs dispute-oriented questions with lease text and supporting contractual evidence, and includes breach categories, structured remedies analysis, evidence-based answers, and uncertainty notes. It supports the development and evaluation of retrieval-augmented legal systems for lease disputes.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A complete answer to the user query grounded in evidence from the contract text. |
| user_query | string | A dispute-oriented question about issues such as unpaid rent, covenant breaches, bankruptcy, cure periods, acceleration, forfeiture, or damages. |
| contract_text | string | The original text of a lease or related contract to be retrieved and analyzed. |
| relief_analysis | object | A structured analysis of cure options, termination, acceleration, and damages following a breach, based on the contractual evidence. |
| contract_evidence | array | Contract clauses, quoted source passages, and explanations of how they relate to the disputed issue and support a conclusion. |
| uncertainty_notes | string | Notes on missing contract text, ambiguous wording, insufficient factual context, or issues requiring further analysis under applicable law. |
| breach_event_types | array | The primary breach or related event types identified from the contract text and user query. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

