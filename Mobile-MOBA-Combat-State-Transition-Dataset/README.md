---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mobile MOBA Combat State Transition Dataset
---

# Mobile MOBA Combat State Transition Dataset

This dataset pairs synthetic text describing pre-combat states, skill or basic attack events, and rule conditions in mobile MOBA games with structured post-event state records. Its fields cover key attributes such as hero health, shields, damage types, control effects, and survival status, supporting the modeling of state changes across combat events. It is suitable for structured-output supervised fine-tuning, combat state prediction, rule reasoning, and game battle simulation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| event_type | string | Type of attack event, such as a skill or basic attack. |
| skill_name | string | Name of the skill used for the attack; set to Basic Attack for a basic attack. |
| damage_type | string | Category of damage dealt by the attack, such as physical, magical, or true damage. |
| target_name | string | Name of the hero affected by the skill or basic attack. |
| attacker_name | string | Name of the hero initiating the skill or basic attack. |
| damage_amount | number | Damage value determined for the attack from the event description and applicable rules. |
| rule_condition | string | Game rule, trigger condition, or damage modifier affecting this state transition. |
| post_target_alive | boolean | Whether the target hero remains alive after the event is resolved. |
| pre_target_health | number | Target hero's current health before the event occurs. |
| pre_target_shield | number | Target hero's shield value available to absorb damage before the event occurs. |
| battle_description | string | Synthetic text input describing the pre-combat state, skill or basic attack event, and applicable rule conditions. |
| post_target_health | number | Target hero's remaining current health after applying the event and its rules. |
| post_target_shield | number | Target hero's remaining shield value after applying the event and its rules. |
| transition_summary | string | Brief explanation of event-driven changes to health, shield, control effects, and survival status. |
| health_damage_taken | number | Amount of damage that actually reduces the target's health during the event. |
| post_control_effect | string | Control effect affecting the target after the event is resolved, or None if there is no control effect. |
| pre_target_max_health | number | Target hero's maximum health in this combat state record. |
| applied_control_effect | string | Control effect applied to the target by the event, or None if no control effect is applied. |
| shield_absorbed_damage | number | Amount of damage absorbed by the target's shield during the event. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

