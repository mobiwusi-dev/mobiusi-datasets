---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Psychotherapy Crisis Response Protocol Constraint Verification Benchmark
---

# Psychotherapy Crisis Response Protocol Constraint Verification Benchmark

This benchmark represents risk-related psychotherapy service scenarios, applicable workflow rules, and proposed follow-up actions in JSON, with labels indicating which constraints are satisfied, violated, or left unaddressed. Each assessment includes a concise rationale to support evaluation of a model's constraint reasoning and verification in crisis response workflows. It is suited to domain-specific model evaluation, protocol analysis, and structured assessment research.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| risk_scenario | object | The risk-related client situation provided as an input source. |
| protocol_rules | array | The service-process rules supplied as an input source for evaluating the proposed actions. |
| omitted_constraints | array | Identifiers of applicable protocol constraints not addressed by the proposed actions. |
| assessment_rationale | string | A concise explanation supporting the compliance, violation, and omission labels. |
| violated_constraints | array | Identifiers of protocol constraints contradicted by the proposed actions. |
| compliant_constraints | array | Identifiers of protocol constraints satisfied by the proposed actions. |
| proposed_follow_up_actions | array | The proposed next steps supplied as an input source for protocol validation. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

