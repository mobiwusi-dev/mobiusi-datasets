---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Comprehensive Q&A Dataset on Chromatographic Method and Instrument Compatibility
---

# Comprehensive Q&A Dataset on Chromatographic Method and Instrument Compatibility

This dataset provides long-form question-and-answer examples about the compatibility of chromatographic methods, sample requirements, and instrument constraints. Topics include flow rate, pressure, temperature, columns, mobile phases, injection modes, and system configurations, with each example pairing a compatibility question with a clear conclusion, expert reasoning, and practical adjustment recommendations where needed. It is designed for domain-specific supervised fine-tuning, Q&A evaluation, and technical support applications in chromatography instrumentation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| expert_answer | string | Combines method conditions, sample requirements, and instrument constraints to explain the compatibility assessment and the relationships among relevant parameters or configurations. |
| recommendations | string | When incompatibilities or conditions apply, describes feasible parameter adjustments, configuration changes, or points requiring further confirmation. If no changes are needed, it may state that no adjustment is required. |
| method_conditions | string | Describes the chromatographic method's flow rate, pressure, temperature, column, mobile phase, and other analytical conditions. |
| sample_requirements | string | Describes sample properties, preparation requirements, injection volume, and other analysis- or injection-related requirements. |
| compatibility_status | string | Summarizes whether the method and instrument are compatible, using a clear conclusion such as fully compatible, compatible with conditions, or incompatible. |
| compatibility_question | string | Poses a specific question that requires assessing compatibility among the given method, sample, and instrument conditions. |
| instrument_constraints | string | Describes instrument specifications or limits, including flow rate, pressure, temperature, injection mode, and system configuration. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

