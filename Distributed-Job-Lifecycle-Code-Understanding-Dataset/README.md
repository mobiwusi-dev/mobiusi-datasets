---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Distributed Job Lifecycle Code Understanding Dataset
---

# Distributed Job Lifecycle Code Understanding Dataset

Focused on job creation, state transitions, execution completion, and persistence in distributed task and job scheduling systems, this dataset pairs source code excerpts with code-understanding questions and demonstration answers. It covers relevant call paths, state changes, and conditions that affect execution outcomes, supporting training and evaluation of models that explain scheduler behavior from code. Typical uses include code instruction tuning, development assistance for scheduling systems, and code-understanding benchmark construction.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A precise answer to the question, grounded in the supplied source code. |
| question | string | The code-understanding question to answer using the supplied source code. |
| call_path | array | The relevant sequence of methods or functions implementing the behavior, ordered from entry point to outcome where possible. |
| source_code | string | The source code excerpt used as evidence for analyzing job lifecycle behavior. |
| key_conditions | array | Branches, guards, or other conditions that affect job state changes, completion, or persistence. |
| source_evidence | array | Relevant code references supporting the explanation, such as symbols, file paths, or line ranges. |
| lifecycle_summary | string | A concise explanation of the relevant job lifecycle behavior and its outcome. |
| state_transitions | array | The job state changes supported by the source code, in execution order where determinable. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

