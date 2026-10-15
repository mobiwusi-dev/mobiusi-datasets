---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Patent Eligibility Case Retrieval Dataset
---

# Patent Eligibility Case Retrieval Dataset

This benchmark brings together court judgments, administrative decisions, examination opinions, and applicant responses concerning patent subject matter eligibility, alongside claim and technical-solution text. It links technical descriptions, examination objections, applicable standards, legal reasoning, and related precedent arguments to support evaluation of how well RAG systems retrieve analogous legal reasoning and authority in patent prosecution. It is suited to legal retrieval benchmarking, precedent analysis, and patent examination research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| claim_text | string | Original text of the patent claims or proposed subject matter under evaluation. |
| decision_basis | array | Key facts, technical features, legal rules, and arguments supporting the final disposition. |
| decision_outcome | string | Final determination of patent subject matter eligibility, such as eligible, ineligible, partially eligible, or unclear. |
| related_precedents | array | Precedents and associated legal propositions identified from judgments, administrative decisions, or external case materials for retrieval in analogous cases. |
| court_judgment_text | string | Full text or excerpt of a court judgment concerning patent subject matter eligibility. |
| retrieval_relations | array | Retrieval links among technical-solution descriptions, examination objections, and related precedent arguments for evaluating legal reasoning retrieval in RAG systems. |
| source_case_metadata | object | Original identification and source information for the case, application, or document. |
| document_type_summary | array | Document types represented in the record, classified from the source materials. |
| examination_objections | array | Eligibility objections, legal grounds, and response outcomes extracted from examination opinions, administrative decisions, or related documents. |
| applicant_response_text | string | Original text of the applicant's response, written arguments, or amendment explanation addressing an eligibility opinion or objection. |
| legal_reasoning_summary | string | Summary of the eligibility reasoning chain synthesized from judgments, decisions, examination opinions, and applicant responses. |
| technical_solution_text | string | Original description of the applicant's technical solution, technical means, and operating method. |
| examination_opinion_text | string | Full text or excerpt on subject matter eligibility from an examination opinion, office action, or rejection rationale. |
| eligibility_issue_summary | string | Structured summary of the central issue: whether the claimed subject matter qualifies as patent-eligible subject matter. |
| claimed_subject_matter_type | string | Subject matter type identified from the claims and technical solution, such as a computer program, business method, mathematical method, natural phenomenon, or system with technical features. |
| administrative_decision_text | string | Full text or excerpt of an administrative, review, or invalidation decision concerning patent subject matter eligibility. |
| technical_contribution_analysis | string | Extracts and analyzes the technical contribution of the solution in relation to an abstract idea, natural phenomenon, or prior art. |
| applicable_eligibility_standards | array | Applicable legal standards, decision steps, or examination tests derived from the source materials. |
| abstract_idea_or_natural_phenomenon | boolean | Indicates whether the claimed subject matter is found or argued to involve an abstract idea, mathematical method, law of nature, or natural phenomenon. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

