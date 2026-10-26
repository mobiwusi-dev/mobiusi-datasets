---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Painting Attribution and Workshop Relationship Multi-Hop Reasoning QA Dataset
---

# Painting Attribution and Workshop Relationship Multi-Hop Reasoning QA Dataset

This dataset presents questions and reference answers about painting attribution, relationships between artists and workshops, and related catalog records, requiring the integration of multiple textual clues. Each example includes supporting evidence, an attribution analysis, and ordered reasoning steps to help models assess differences across sources and address disputed attribution cases. It supports multi-hop question answering, reasoning fine-tuning, and evaluation in painting heritage research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A concise answer that directly states the supported attribution or relationship. |
| evidence | array | Evidence linked to its sources that supports the answer and attribution assessment. |
| raw_case | object | The original question and source materials provided as inputs for attribution reasoning. |
| reasoning_steps | array | Ordered multi-step reasoning that connects source evidence to the final answer. |
| attribution_analysis | object | A synthesized assessment of the painting attribution and any differences among records. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

