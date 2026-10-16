---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: GRE Reading Comprehension Background Knowledge Evidence Retrieval Dataset
---

# GRE Reading Comprehension Background Knowledge Evidence Retrieval Dataset

This dataset connects GRE reading passages with academic topics, background concepts, clarification questions, and related webpage text. It includes analyses of passage claims and evidence paragraphs that support or qualify those claims, while distinguishing information stated in the passage from facts that require external sources. It supports training and evaluation of background knowledge retrieval, evidence linking, and information-boundary identification.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| academic_topic | string | The main academic field or research topic identified from the GRE passage and related background materials. |
| claim_analysis | array | An analysis of important passage claims, including their information scope, clarification results, and the relationship between each claim and external evidence. |
| gre_passage_text | string | The full GRE reading passage to be analyzed. It serves as the source input for identifying academic topics, textual claims, and the boundaries of background knowledge. |
| background_concepts | array | Key concepts, terms, theories, or historical facts that help explain the passage or answer the clarification question. |
| evidence_paragraphs | array | Complete passages identified in related webpage text that support or qualify claims in the reading passage, with an explanation of each passage's role. |
| source_webpage_text | string | The original text or main content of a webpage related to the clarification question or passage topic, serving as a source of external background information. |
| information_boundary | object | A summary distinguishing information stated directly in the reading passage from information that requires external background sources, helping separate passage evidence from external evidence. |
| clarification_question | string | A question about an academic topic, background concept, or passage claim that requires clarification using external sources. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

