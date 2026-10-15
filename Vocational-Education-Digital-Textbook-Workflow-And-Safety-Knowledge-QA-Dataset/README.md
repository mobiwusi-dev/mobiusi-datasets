---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Vocational Education Digital Textbook Workflow and Safety Knowledge QA Dataset
---

# Vocational Education Digital Textbook Workflow and Safety Knowledge QA Dataset

This dataset provides learner-focused professional knowledge questions and answers based on vocational education web textbooks, covering equipment operation, process workflows, technical requirements, risk warnings, and fault prevention. Web text is organized into fields for knowledge categories, operation steps, safety requirements, risks, preventive measures, and supporting source excerpts, making the data suitable for domain-specific fine-tuning, question answering, and evaluation of safety-procedure understanding. The sample count and subject coverage are not specified in the available information; the delivered data determines the actual scope.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An accurate and complete answer based on the source textbook content and consistent with relevant professional rules. |
| question | string | A professional knowledge question for learners, derived from the source textbook content. |
| source_html | string | Original vocational education textbook webpage content serving as the source for the questions and answers, with web text retained as the natural content format. |
| risk_warnings | array | Potential hazards, possible consequences, and other risk information highlighted in the textbook content. |
| operation_steps | array | Equipment operation or process steps extracted from the answer and ordered by execution sequence; may be an empty array for non-procedural knowledge. |
| evidence_excerpt | string | A key excerpt from the textbook that supports the question and answer and allows their source to be traced. |
| fault_prevention | array | Measures extracted from the textbook content to help prevent equipment faults, process deviations, or operational errors. |
| knowledge_category | string | The category assigned to the type of knowledge covered by the question and answer. |
| safety_requirements | array | Safety practices, technical standards, work restrictions, or compliance requirements extracted from the textbook content. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

