---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cross-Passage Question Answering for Religious Texts
---

# Cross-Passage Question Answering for Religious Texts

Designed for religious text research and domain-specific model training, this collection contains questions that require information from multiple passages, including thematic echoes, causal links, event sequences, supplementary details, and contrasts. Each example provides a question, the text and relevant passage materials, an answer with supporting evidence, and an explanation of the relationships used. It supports evidence integration and traceable responses within a defined corpus, as well as closed-domain QA and domain expert SFT.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct response synthesized from relevant passages in the source text. |
| evidence | array | The source passages and specific quotations that support the answer. |
| reasoning | string | An explanation of how information from different passages is connected to derive the answer. |
| relation_type | string | The relationship between the passages used, such as thematic echo, causal link, event sequence, supplementary explanation, or contrast. |
| source_material | string | The original input, including the question, the title of the religious text, and the identifiers and contents of relevant passages. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

