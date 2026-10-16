---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Employment Contract Termination and Severance Clause Retrieval Dataset
---

# Employment Contract Termination and Severance Clause Retrieval Dataset

This dataset focuses on probationary dismissal, notice periods, immediate dismissal, automatic termination, exit handover, severance, and compensation conditions in employment contracts. It provides retrieval-oriented samples while preserving source legal-document excerpts and provenance information that can support answers. Entries are organized by clause category, triggering event, applicable scope, notice rules, and compensation rules, supporting evidence retrieval, source tracing, and context assembly for employment termination workflows. It is designed for building and evaluating legal-document RAG retrieval pipelines; specific conclusions should be checked against applicable law and reviewed by qualified professionals.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| notice_rule | object | Extracts notice requirements for ending or terminating the employment relationship from the source excerpt. |
| source_record | object | Preserves the original legal document and its source information for retrieval and evidence tracing. |
| evidence_spans | array | Identifies key supporting excerpts in the source legal document and their locations. |
| severance_rule | object | Structurally records eligibility, calculation methods, and payment arrangements for severance or other employment-related compensation. |
| clause_category | string | Identifies the primary clause category derived from the source document. |
| applicable_scope | string | Specifies the employers, employees, probationary employees, roles, or other groups covered by the clause. |
| confidence_score | number | Indicates overall confidence in the extracted clause category, eligibility conditions, and compensation rules, on a scale from 0 to 1. |
| retrieval_queries | array | Provides user questions, synonymous expressions, or keywords generated from the clause content for RAG retrieval. |
| termination_trigger | string | Summarizes the facts, conduct, expiry of a term, or other legal event that triggers termination of the employment contract. |
| exceptions_or_limits | array | Extracts exceptions and limitations concerning termination notice, compensation, or handover requirements. |
| handover_obligations | array | Extracts requirements for transferring work, documents, property, or access rights when an employee leaves. |
| compensation_conditions | array | Lists the conditions required to receive severance, pay in lieu of notice, or other compensation. |
| supporting_answer_summary | string | Provides a concise, evidence-based summary for assembling retrieval context in employment termination scenarios. |
| immediate_termination_basis | array | Lists statutory or contractual grounds for ending the employment relationship without advance notice. |
| automatic_termination_condition | string | Summarizes conditions under which an employment contract automatically ends due to expiry, a specified event, or a legal rule. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

