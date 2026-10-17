---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: NB-IoT End-to-End Data Path Fault Localization QA Dataset
---

# NB-IoT End-to-End Data Path Fault Localization QA Dataset

This dataset focuses on NB-IoT uplink and downlink service anomalies, pairing anomaly reports with textual observations from the access network, core network, and service connection path. Its question-and-answer records organize diagnostic questions, stepwise elimination reasoning, and final fault assessments across key segments of the end-to-end data path. It supports fault-localization reasoning training, diagnostic QA evaluation, and research on NB-IoT network operations; the sample count and other scale details have not been provided.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| confidence | number | Estimated confidence in the selected fault location, expressed as a value from 0 to 1. |
| final_answer | string | Direct answer to the diagnostic question, summarizing the most likely fault location and the main supporting rationale. |
| fault_hypothesis | string | Concise explanation of the likely fault mechanism and its location, grounded in the supplied observations. |
| elimination_steps | array | Ordered diagnostic steps that assess evidence and eliminate or retain possible fault locations along the data path. |
| traffic_direction | string | Direction of the affected NB-IoT business traffic. |
| anomaly_description | string | User-reported or system-reported description of the abnormal NB-IoT service behavior. |
| diagnostic_question | string | Question to be answered by tracing and localizing the fault along the end-to-end NB-IoT data path. |
| core_network_observation | string | Textual observations or diagnostic results for the NB-IoT core network portion of the data path. |
| access_network_observation | string | Textual observations or diagnostic results for the device and radio access network portion of the data path. |
| most_likely_fault_location | string | The end-to-end path segment most likely responsible for the reported anomaly. |
| service_connection_observation | string | Textual observations or diagnostic results for the connection between the core network and the destination service or application. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

