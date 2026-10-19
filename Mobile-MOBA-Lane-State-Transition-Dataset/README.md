---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mobile MOBA Lane State Transition Dataset
---

# Mobile MOBA Lane State Transition Dataset

This dataset contains synthetic text events covering lane advances, minion engagements, lane clearing, and interactions with defensive towers in mobile MOBA games. Structured fields capture the pre-event state, event category, resulting state, and transition summary, including changes in minion survival, lane position, and push status. It supports training models to predict the next state from an event and its preceding state, as well as evaluating structured reasoning about lane evolution. The content focuses on lane mechanics rather than hero combat or map objectives.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| event_text | string | Original synthetic event text describing a lane advance, minion engagement, lane clearing, or defensive tower interaction. |
| next_state | object | The next lane state inferred from the event text and the pre-event state. |
| initial_state | object | The state of both sides' lanes before the event, including minion survival, lane phase, push status, and defensive tower interaction status. |
| event_category | string | The primary lane evolution category inferred from the event text. |
| transition_summary | string | A brief explanation of how the event changes minion survival, lane position or phase, push status, or defensive tower interaction status. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

