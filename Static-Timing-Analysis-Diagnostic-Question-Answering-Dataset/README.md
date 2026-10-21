---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Static Timing Analysis Diagnostic Question Answering Dataset
---

# Static Timing Analysis Diagnostic Question Answering Dataset

Designed for timing analysis in digital circuit systems, this dataset provides long-form contexts combining timing constraints, clock definitions, static timing analysis reports, and relevant RTL or netlist descriptions. Questions address critical paths, causes of timing violations, and potential repair directions, with answers that synthesize report evidence and design context. It supports domain-specific supervised fine-tuning and evaluation of timing-analysis question answering.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A domain-specific answer that combines timing report evidence and design context to address the question. |
| question | string | A question about a critical path, the cause of a timing violation, or a possible timing improvement. |
| sta_report | string | A static timing analysis report containing path details, arrival and required times, slack, and violation information. |
| violation_causes | array | A list of evidence-based causes that may explain the timing violation. |
| clock_definitions | string | Clock definition text, including clock periods, waveforms, generated clocks, and relationships between clocks. |
| repair_directions | array | A list of possible design or constraint changes that could address the identified timing issue. |
| design_description | string | Relevant RTL, netlist, or design explanation that provides context for interpreting the reported timing paths. |
| timing_constraints | string | Timing constraint text relevant to the design, such as input and output delays, false paths, and multicycle paths. |
| critical_path_summary | string | A concise explanation of the relevant startpoint, endpoint, path characteristics, and timing result. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

