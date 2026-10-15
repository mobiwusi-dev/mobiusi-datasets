---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Virtual Biological Experiment Protocol Fact Verification Dataset
---

# Virtual Biological Experiment Protocol Fact Verification Dataset

This dataset brings together protocols from virtual biological experiment webpages, covering sample handling, cell or microbial culture, genetic experiments, ecological observation, and testing. Records organize source HTML, cleaned protocol text, experimental conditions, and procedural steps, and may include claims about experimental conditions, biological processes, or results paired with evidence spans, verdicts, confidence scores, and explanations. It supports training and evaluating models for evidence retrieval, claim verification, and reasoning over constraints in specialized biological web content.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| verdict | string | The factual judgment made about the claim based on the experimental protocol text and evidence spans. |
| claim_text | string | A claim about experimental conditions, biological processes, or experimental results that must be checked against the protocol text. |
| confidence | number | The confidence score for the fact verification verdict, ranging from 0 to 1. |
| protocol_text | string | Protocol text extracted from the source webpage and cleaned for use. |
| evidence_spans | array | Source text excerpts and their locations that support, refute, or do not directly resolve the claim. |
| protocol_steps | array | Protocol operations organized in the order in which the experiment is performed. |
| protocol_category | string | The primary biological experiment category identified from the protocol content. |
| protocol_page_html | string | The original webpage HTML containing sample handling, culture, genetic experiment, ecological observation, or testing protocols. |
| verification_reason | string | An explanation of the verdict based on experimental conditions, biological processes, and evidence spans. |
| experimental_subjects | array | Samples, cells, microorganisms, genes, or ecological subjects extracted from the protocol. |
| experimental_conditions | object | Conditions and constraints extracted from the protocol, such as temperature, duration, culture medium, and gas environment. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

