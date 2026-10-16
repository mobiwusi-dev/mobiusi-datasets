---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Korean Document Ambiguity and Implicit Meaning Understanding Benchmark Dataset
---

# Korean Document Ambiguity and Implicit Meaning Understanding Benchmark Dataset

This benchmark covers challenging phenomena in Korean documents, including omitted subjects, honorific tone, negation, conditional exceptions, ambiguous references, polysemy, and polite refusals. Its JSON records organize the source document, ambiguity points, candidate interpretations, correct semantics, and semantic parses. The examples support domain-specific supervised fine-tuning and evaluation of document understanding, helping identify gaps in contextual and pragmatic reasoning.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| raw_document | object | The original Korean document before semantic analysis, along with basic contextual information. |
| semantic_parse | object | A structured analysis of challenging language phenomena that explains the reasoning from the source text to the correct meaning. |
| ambiguity_points | array | Locations in the source text involving omissions, negation, conditions, references, polysemy, or pragmatics, with explanations of the ambiguity. |
| correct_semantics | object | The intended meaning and communicative function determined from the context and Korean pragmatic conventions. |
| candidate_interpretations | array | Possible semantic interpretations of the document or its key ambiguity points, with assessments of supporting evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

