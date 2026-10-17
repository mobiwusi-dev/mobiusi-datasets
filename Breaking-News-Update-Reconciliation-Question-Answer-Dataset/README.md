---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Breaking News Update Reconciliation Question-Answer Dataset
---

# Breaking News Update Reconciliation Question-Answer Dataset

This dataset features questions that require comparing multiple excerpts from continuously updated breaking news reports, along with their answers. It distinguishes confirmed facts from unconfirmed or disputed claims and records corrections and updates, with evidence citations and reasoning summaries. It supports training and evaluating models that integrate evidence across texts, track changing information, and produce carefully qualified conclusions.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| reports | array | The source reports and update excerpts provided as inputs for reconciliation. |
| question | string | The question to answer by comparing the supplied news report excerpts. |
| confirmed_facts | array | Facts explicitly established or consistently confirmed by the supplied reports. |
| reasoning_summary | string | A concise explanation of how the excerpts were compared and how the final supported conclusion was reached. |
| evidence_citations | array | Traceable excerpts that support, contradict, qualify, or correct the answer and claim assessments. |
| corrections_and_updates | array | Material changes in wording or factual status across successive reports. |
| current_supported_answer | string | A concise answer limited to conclusions supported by the supplied reports at the latest available update. |
| unconfirmed_or_disputed_claims | array | Claims whose status remains uncertain, conflicting, corrected, or otherwise not established by the latest reports. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

