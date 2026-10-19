---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Mobile Casual Game Monetization Integration Code Completion Dataset
---

# Mobile Casual Game Monetization Integration Code Completion Dataset

This dataset covers ad display, rewarded ad callbacks, and in-app purchase flows in mobile casual games, with task instructions, Lua or Luau code context, and target completions. The samples focus on SDK invocation timing, callback branches, error and lifecycle handling, and updates to in-game reward state. They support training and evaluating code models for mobile game monetization integration.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| code_prefix | string | Provides the code preceding the completion point, written in Lua or Luau and showing game logic, SDK calls, or callback context. |
| code_language | string | Identifies the language used in the code to be completed. |
| completion_code | string | Provides the target code generated from the task instruction and code context, including monetization SDK calls and relevant error, lifecycle, or callback handling. |
| callback_handling | string | Summarizes how success, failure, close, or cancellation callbacks are handled, including safeguards against duplicate callbacks when needed. |
| invocation_timing | string | Explains when key ad or purchase interfaces should be called and how invocation relates to game state and page lifecycle. |
| completion_instruction | string | Describes the monetization integration task to complete, including expected behavior or code requirements. |
| reward_state_transition | string | Explains how in-game rewards, items, or player state are validated and updated after a rewarded ad or purchase succeeds. |
| commercialization_scenario | string | Summarizes the primary monetization integration scenario represented by the completion. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

