---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Traditional Metalworking Craft Question Answering Dataset
---

# Traditional Metalworking Craft Question Answering Dataset

This dataset organizes reference material on traditional metalworking techniques, including forging, casting, chasing, and welding, into questions and answers grounded in the source text. Each record can link a source passage with a technique type, supporting evidence quote, relevant tools, and ordered process steps, making answer provenance easier to verify. It supports craft knowledge retrieval, open-book question answering, retrieval-augmented generation, and heritage education.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| tools | array | Tools mentioned in the source text that are relevant to the question or answer. |
| answer | string | An answer to the question grounded in the source text. |
| question | string | A question about the technique that can be answered using the source text. |
| source_text | string | Original reference passage describing a traditional metalworking technique, tool, or process. |
| process_steps | array | The ordered steps of the metalworking process described in the source text. |
| evidence_quote | string | A verbatim excerpt from the source text that supports the answer. |
| technique_type | string | The metalworking technique discussed, such as forging, casting, chasing, or welding. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

