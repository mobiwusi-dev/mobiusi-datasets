---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: AR Try-On Tracking State Transition Evaluation Dataset
---

# AR Try-On Tracking State Transition Evaluation Dataset

This dataset contains simulated sequences of user body motion, camera viewpoint changes, and virtual garment anchor positions, along with reference tracking-state labels over time and events marking transitions between consecutive states. Sequence-level recovery summaries capture tracking loss and recovery behavior, enabling evaluation of how models represent and predict tracking-state changes. It is suited to assessing stable garment following, viewpoint adaptation, and tracking recovery in AR retail try-on.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| recovery_summary | object | Sequence-level metrics summarizing tracking loss and recovery behavior. |
| transition_events | array | Temporal events marking changes between consecutive reference tracking states. |
| sequence_observations | object | Simulated observations across frames, including body motion, camera viewpoints, and virtual garment anchor positions. |
| reference_tracking_states | array | Reference labels specifying the tracking state at each point in the sequence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

