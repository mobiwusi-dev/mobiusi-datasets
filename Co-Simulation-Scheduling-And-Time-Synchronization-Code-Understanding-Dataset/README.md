---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Co-Simulation Scheduling and Time Synchronization Code Understanding Dataset
---

# Co-Simulation Scheduling and Time Synchronization Code Understanding Dataset

This dataset contains source code understanding samples focused on co-simulation master controllers and scheduling components, including simulation step sizes, execution order, time advancement, and synchronization control. Each sample pairs source code with an analysis question and an answer, and includes explanations of control flow, execution order, and timing relationships. It supports code SFT training and evaluation for understanding scheduling implementations in co-simulation tools, rather than generating or configuring simulation models.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| source_code | string | Source code from a co-simulation master controller or scheduling component to be analyzed. |
| execution_order | array | An ordered list of co-simulation components or scheduling stages, with an explanation of each stage. |
| analysis_question | string | A code understanding task or analysis question about the source code. |
| understanding_answer | string | An accurate answer based on the source code that explains the scheduling implementation and its key behaviors. |
| control_flow_explanation | string | An explanation of the call path, branch conditions, loop behavior, and changes in control flow across scheduling-related functions or modules. |
| timing_and_synchronization_explanation | string | An explanation of simulation step sizes, time advancement methods, synchronization conditions, and timing relationships between components. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

