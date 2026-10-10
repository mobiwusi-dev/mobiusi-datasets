---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Giant Freshwater Prawn Growth and Feed Efficiency Causal Reasoning QA Dataset
---

# Giant Freshwater Prawn Growth and Feed Efficiency Causal Reasoning QA Dataset

This dataset provides question-and-answer text about growth performance and feed efficiency in giant freshwater prawns, covering feed, feeding methods, stocking density, water temperature, molting stage, and other farming factors. Each record includes a question, background and evidence, an answer, causal reasoning, a causal caveat, and a management implication, supporting evidence-based analysis of potential mechanisms and the distinction between correlation and causation. It can support aquaculture management QA, causal reasoning evaluation, and reasoning-focused supervised fine-tuning (SFT); no fixed sample count or coverage statistics are provided.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An accurate, concise response that states the conclusion supported by the evidence and its applicable scope. |
| evidence | string | The farming context, observations, experimental information, or other evidence provided to support the answer. If relevant evidence is unavailable, this should be stated explicitly. |
| question | string | A question about how feed, feeding methods, stocking density, water temperature, molting stage, or other farming factors may affect giant freshwater prawn growth or feed efficiency. |
| causal_caveat | string | States whether the available information supports a causal conclusion, clarifies that correlated changes do not establish causation, and identifies possible confounders, alternative explanations, or evidence gaps. |
| causal_reasoning | string | Explains how a factor might affect growth performance or feed efficiency through a potential mechanism, grounding the reasoning in the available context and evidence. |
| management_implication | string | Provides cautious guidance relevant to giant freshwater prawn farming without exceeding what the evidence supports. When evidence is insufficient, it identifies information or validation needed. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

