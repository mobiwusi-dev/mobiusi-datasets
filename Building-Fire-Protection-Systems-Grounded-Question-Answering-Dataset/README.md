---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Building Fire Protection Systems Grounded Question Answering Dataset
---

# Building Fire Protection Systems Grounded Question Answering Dataset

This dataset covers the components, status information, and source-documented operating cautions of building fire protection systems, including sprinklers, indoor hydrants, fire alarms, smoke control, and other systems. Each question-answer record is linked to source material and includes an answerability label, a system category, and supporting evidence; when the source is insufficient, the response should state that the answer cannot be determined from the available material. It supports closed-domain question answering training and evaluation for building fire response, helping models produce cautious, traceable answers grounded in specified documents.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A professional answer in the context of building fire response, based on the source material. If the source is insufficient, state that the answer cannot be determined from the available material. |
| evidence | string | A quotation or accurate paraphrase from the source material that supports the answer. If the source is insufficient, identify the missing evidence. |
| question | string | A question about building fire protection system components, status information, or operating cautions. |
| answerability | string | Indicates whether the source material provides enough support to answer the question. Mark as insufficient when it does not. |
| source_material | string | Text from building fire protection system descriptions, building documents, or operating files used to answer the question. Answers must be grounded in this material. |
| system_category | string | The system category identified from the question and source material, such as sprinklers, indoor hydrants, fire alarms, or smoke control. |
| operation_cautions | string | Operating cautions explicitly stated in the source material. If none are provided, indicate that no relevant guidance is available; do not add cautions independently. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

