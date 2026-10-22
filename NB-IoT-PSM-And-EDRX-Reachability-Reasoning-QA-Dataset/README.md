---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: NB-IoT PSM and eDRX Reachability Reasoning QA Dataset
---

# NB-IoT PSM and eDRX Reachability Reasoning QA Dataset

This dataset presents question-answer scenarios about NB-IoT device Power Saving Mode (PSM), extended Discontinuous Reception (eDRX) paging opportunities, application downlink timing, and service conditions. Each example uses the supplied timing information to determine whether a device is reachable now, must wait for a wake or paging opportunity, is unavailable within the service window, or cannot be assessed from the available details, and explains the expected delay. Structured answers include the scenario, question, reachability status, delay estimate, reasoning steps, and final answer for NB-IoT operations analysis, device communication management, and reasoning SFT.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| question | string | Source question asking whether the device is reachable and what response delay or latency cause is expected. |
| final_answer | string | Concise answer to the source question, combining the reachability conclusion and expected response delay assessment. |
| latency_reason | string | Explanation of the timing factors responsible for the estimated response delay, such as PSM sleep duration, eDRX paging opportunities, or application downlink timing. |
| reasoning_steps | array | Ordered steps showing how the supplied timing and service conditions lead to the reachability and latency conclusions. |
| scenario_context | string | Source text describing the device power-saving mode, relevant timers and paging cycles, application downlink timing, and service conditions. |
| reachability_status | string | Reasoned classification of whether the device is reachable now, reachable after a wake or paging opportunity, unavailable within the relevant service window, or not assessable from the given information. |
| estimated_response_delay | string | Reasoned response delay estimate, including a value and unit when supported by the scenario, or a qualitative estimate when exact timing cannot be determined. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

