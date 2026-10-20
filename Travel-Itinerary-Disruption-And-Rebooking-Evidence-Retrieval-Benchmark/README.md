---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Travel Itinerary Disruption and Rebooking Evidence Retrieval Benchmark
---

# Travel Itinerary Disruption and Rebooking Evidence Retrieval Benchmark

This benchmark covers cancellations, delays, and other travel itinerary disruptions, pairing travel provider web notices and ticket rules with questions, answers, and source information. Its examples focus on finding the rebooking, refund, or follow-up guidance that applies to a specific disruption scenario, enabling evaluation of evidence retrieval and answer grounding. Source documents and evidence spans support retrieval verification and retrieval-augmented generation testing.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer_text | string | A concise answer grounded in the source document and tailored to the question. |
| user_question | string | A question requesting evidence-based guidance for a travel disruption scenario. |
| evidence_spans | array | Exact passages and source locations that support the answer. |
| disruption_type | string | The disruption addressed by the question or source, such as a cancellation, delay, or other itinerary disruption. |
| source_document | object | The original travel provider webpage or ticket rule text, together with identifying source metadata. |
| applicable_action | string | The rebooking, refund, or other follow-up action supported by the source. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

