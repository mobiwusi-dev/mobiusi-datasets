---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Rootkit Forensic Evidence Synthesis Question Answering Dataset
---

# Rootkit Forensic Evidence Synthesis Question Answering Dataset

This dataset pairs investigation questions with detailed expert analyses based on textual findings from memory, file systems, system logs, and runtime state. It focuses on reconstructing suspected rootkit activity from multiple evidence sources, distinguishing direct observations from analytical inferences, and addressing conflicting evidence, uncertainty, and examination limits. It supports domain-specific supervised fine-tuning, forensic analysis training, and generative question answering evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| expert_answer | string | An analysis that reconstructs suspected rootkit activity across evidence sources; distinguishes direct observations from inferences; explains supporting reasoning, conflicting evidence, uncertainty, and evidentiary limits; and presents a cautious investigative conclusion. |
| evidence_report | string | Textual findings from memory, file system, system log, and runtime state examinations. May include source identifiers, timestamps, and examination limitations. |
| investigation_question | string | A question about suspected rootkit activity, formulated from the forensic evidence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

