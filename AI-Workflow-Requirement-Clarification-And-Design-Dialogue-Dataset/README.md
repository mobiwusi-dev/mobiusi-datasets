---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: AI Workflow Requirement Clarification and Design Dialogue Dataset
---

# AI Workflow Requirement Clarification and Design Dialogue Dataset

This dataset focuses on multi-turn conversations between users and assistants about automation needs, covering key details such as goals, trigger conditions, workflow steps, constraints, and expected outcomes. The dialogues show how an assistant can identify requirements, ask for missing information, and develop a workflow proposal. It supports dialogue SFT and evaluation of requirement understanding, clarification, and workflow design for orchestration assistants.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| constraints | string | User-stated restrictions, prerequisites, permissions, or other limitations that the workflow must respect. |
| dialogue_text | string | The complete multi-turn conversation between the user and assistant about the desired automation workflow. |
| workflow_steps | string | The proposed workflow actions in their intended order, including important inputs, decisions, or branches. |
| automation_goal | string | The outcome or task the user wants the workflow to automate. |
| expected_result | string | The intended final output or state after the workflow completes successfully. |
| trigger_condition | string | The event, schedule, or condition that starts the workflow, including relevant details clarified in the dialogue. |
| final_workflow_plan | string | A consolidated natural-language workflow proposal incorporating the clarified goal, trigger, steps, constraints, and expected result. |
| conversation_summary | string | A concise summary of the key clarifications and decisions made during the conversation. |
| unresolved_questions | string | Important requirements or implementation details that remain unclear or unanswered at the end of the dialogue. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

