---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mobile Application Reverse Engineering and Security QA Dataset
---

# Mobile Application Reverse Engineering and Security QA Dataset

This dataset is designed for mobile application reverse engineering and security analysis. Each sample pairs an analysis question with evidence such as textual decompiled code snippets, application manifest content, and runtime observations, followed by an answer, functionality inference, data flow analysis, security assessment, and explanations of evidence and uncertainty. It covers application behavior analysis, sensitive data flow tracing, and security review, with an emphasis on distinguishing observed facts from reasoned conclusions. It supports domain-specific supervised fine-tuning, long-form question answering, and analytical capability evaluation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A direct, coherent answer to the analysis question, distinguishing observed facts from reasoned inferences. |
| question | string | The question to answer about the application's functionality, data flows, or security-related behavior. |
| data_flow_analysis | string | A description of relevant data sources, transformations, destinations, and boundaries, including sensitive data flows when supported by the evidence. |
| decompiled_snippets | string | Textual excerpts from decompiled application code, with relevant class, method, or location context when available. |
| security_assessment | string | An assessment of security-relevant behavior, potential risks, and their conditions or impact, avoiding claims unsupported by the evidence. |
| application_manifest | string | The application manifest content, such as AndroidManifest.xml, including relevant permissions, components, and configuration. |
| runtime_observations | string | Textual observations collected while the application is running, such as logs, network behavior, or user-interface behavior. |
| evidence_and_reasoning | string | The supporting evidence and reasoning that connect specific source snippets, manifest entries, or runtime observations to the conclusions. |
| functionality_inference | string | An explanation of the relevant application feature or behavior inferred from the supplied evidence. |
| uncertainties_and_limits | string | Unresolved questions, alternative explanations, missing evidence, and limitations that affect confidence in the analysis. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

