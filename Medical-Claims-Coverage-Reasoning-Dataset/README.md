---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Medical Claims Coverage Reasoning Dataset
---

# Medical Claims Coverage Reasoning Dataset

This dataset organizes medical insurance claim cases around plan provisions, billed services and costs, visit details, and exclusions, with labels indicating whether a specific expense meets coverage conditions. Each example calls for multi-hop question answering that connects policy language, case facts, and exclusions to produce a coverage outcome, its rationale, relevant provisions, and any unresolved facts. It supports reasoning SFT, training, and evaluation for medical claims workflows.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| policy_terms | string | Source text containing the applicable insurance plan provisions, coverage limits, and benefit conditions. |
| coverage_status | string | Determination of whether the claimed service is covered, partially covered, not covered, or cannot be determined from the available information. |
| exclusion_terms | string | Source text containing applicable exclusions, limitations, and exceptions that may affect coverage. |
| service_details | string | Source text describing the billed medical service, procedure, or item and its claimed cost. |
| unresolved_facts | array | Missing or ambiguous facts that materially limit the coverage determination; an empty array indicates that no such facts remain. |
| visit_information | string | Source text describing the relevant encounter, including dates, diagnoses, provider, and other claim circumstances. |
| coverage_reasoning | string | Explanation connecting relevant plan provisions and exclusions to the service and visit facts. |
| supporting_provisions | array | Specific policy clauses or exclusion provisions that support the coverage determination. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

