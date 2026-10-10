---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Cross-Merchant Beauty Service Catalog Evidence Question Answering Benchmark
---

# Cross-Merchant Beauty Service Catalog Evidence Question Answering Benchmark

This benchmark contains original catalog text from multiple beauty and hair service merchants, questions about service offerings and merchant identity, and corresponding answers with evidence annotations. It records the target merchant, relevant service, catalog evidence quote, evidence merchant, merchant-match status, and whether the answer is supported, enabling evaluation of retrieval and evidence attribution in multi-merchant catalog settings. Typical applications include beauty service discovery, catalog question answering, merchant entity disambiguation, and answer traceability analysis.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | An answer based on the catalog information; if the catalog cannot support an answer, this field should clearly state that it cannot be determined. |
| service_name | string | The service name identified from the question or catalog that is relevant to the answer. |
| user_question | string | A question to answer using the merchant catalog, potentially concerning a service offering or merchant distinction. |
| evidence_quote | string | An excerpt from the catalog that directly supports the answer; leave blank when the catalog contains no relevant evidence. |
| target_merchant | string | The beauty or hair service merchant identified as the target of the question. |
| catalog_document | string | Original catalog text containing beauty and hair service merchants and their offerings; it may include information from multiple merchants. |
| evidence_merchant | string | The merchant associated with the evidence excerpt, used to verify whether the correct merchant's catalog information was cited. |
| is_merchant_match | boolean | Indicates whether the merchant associated with the evidence matches the target merchant in the question. |
| is_answer_supported | boolean | Indicates whether the cited catalog evidence directly supports the answer. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

