---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Traditional Theater Roles and Stage Conventions QA Dataset
---

# Traditional Theater Roles and Stage Conventions QA Dataset

This dataset provides closed-domain question answering on role types, stage conventions, performance rules, and their meanings across traditional theater forms. Each example includes source material, a question, and an answer, with optional fields for knowledge category, source-support status, evidence excerpts, citations, and reasoning notes to make answers traceable. It supports supervised fine-tuning, knowledge-grounded QA, and evidence-faithfulness evaluation for models focused on traditional performing arts.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An answer grounded in the source material. Clearly state when the material does not address a point, and do not present it as a sourced fact. |
| question | string | A question about role types, stage conventions, performance rules, or their meanings across theater forms. |
| source_text | string | The theater materials or specialist literature used to answer the question. |
| reasoning_note | string | Briefly explains how the answer addresses the question, how the evidence supports the conclusion, and how omissions or conflicts in the source are handled. |
| support_status | string | Indicates how the answer's conclusions are supported by the supplied source material. |
| source_citation | string | A citation for the source supporting the answer, compiled from the supplied bibliographic information. Do not invent publication details. |
| evidence_excerpt | string | A direct excerpt from the source that supports the answer. Use an empty string when no relevant evidence is provided. |
| knowledge_category | string | The category of theater knowledge addressed by the question. |
| source_bibliography | string | Author, title, publication details, or other source identifiers provided with the original material. Use an empty string when none are provided. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

