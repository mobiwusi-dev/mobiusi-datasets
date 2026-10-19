---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Online Course Caption Fact Verification Benchmark
---

# Online Course Caption Fact Verification Benchmark

This benchmark focuses on factual claims extracted from transcripts of online course videos and pairs them with relevant web text evidence, verification verdicts, evidence relations, and rationales. Designed for online education content, it supports evaluation of whether models can determine claim validity from textual evidence, assess how the evidence relates to a claim, and explain their decisions. It is suitable for fact-checking system development, model comparisons, and evidence reasoning research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| verdict | string | The judgment about the transcript claim based on the web text evidence. |
| rationale | string | A brief explanation of how the web text evidence supports, refutes, or is insufficient to assess the factual claim. |
| transcript_claim | string | A factual statement extracted from an online course video transcript for verification. |
| evidence_relation | string | Describes how the web text evidence relates to and supports the transcript claim. |
| web_evidence_text | string | Relevant web text used to verify the factual claim from the course transcript. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

