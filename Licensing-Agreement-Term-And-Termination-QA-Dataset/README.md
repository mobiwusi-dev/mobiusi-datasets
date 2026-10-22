---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Licensing Agreement Term and Termination QA Dataset
---

# Licensing Agreement Term and Termination QA Dataset

This dataset contains question-answer examples about licensing agreement terms, renewal conditions, termination triggers, notice requirements, and obligations that survive termination. Each record includes a reference answer and supporting contract provisions, along with structured summaries of topics such as term, renewal, termination, notice, and post-termination duties. It supports training and evaluating retrieval-augmented generation systems for contract retrieval and open-book question answering.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| qa_topic | string | The normalized question subject, such as agreement term, renewal, termination trigger, notice, or surviving obligation. |
| question | string | A question about the term, renewal, termination, notice, or post-termination provisions of a licensing agreement. |
| term_summary | string | A concise structured summary of the initial term, commencement, and expiration details stated in the contract basis. |
| contract_basis | string | The relevant contract excerpt or provision supporting the reference answer, including a clause reference when available. |
| reference_answer | string | The gold-standard answer, based on the cited provisions of the licensing agreement. |
| renewal_conditions | string | A summary of renewal eligibility, renewal periods, automatic renewal terms, and any stated conditions or deadlines. |
| notice_requirements | string | A summary of applicable notice periods, delivery methods, recipients, and timing requirements stated in the contract basis. |
| termination_triggers | string | A summary of events or circumstances that permit or require termination under the contract basis. |
| post_termination_obligations | string | A summary of obligations that continue or arise after termination, such as payment, cessation of use, return or destruction of materials, or confidentiality. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

