---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Kernel Privilege Transition and Boundary Verification Dataset
---

# Kernel Privilege Transition and Boundary Verification Dataset

This dataset focuses on kernel source code samples involving credential changes, capability updates, namespace transitions, and privileged system calls. Each sample is organized around a permission-boundary question or verification objective, with relevant code paths, kernel symbols, findings, and root-cause analysis. It supports coding agent training and research into code-path tracing, permission-boundary verification, and root-cause analysis of local privilege escalation flaws.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| code_path | array | The ordered functions or code locations traced to evaluate the privilege transition. |
| source_code | string | The kernel source code sample to inspect for privilege transition behavior. |
| relevant_symbols | array | Kernel functions, structures, flags, or constants relevant to the analysis. |
| security_boundary | string | The permission boundary or security invariant relevant to the verification objective. |
| root_cause_analysis | string | The code-level explanation of the defect or the reason the expected permission boundary is preserved. |
| verification_passed | boolean | Whether the source-code analysis confirms the stated verification objective. |
| verification_findings | array | Evidence-based findings that address the verification objective. |
| verification_objective | string | The permission-boundary question or verification target associated with the source sample. |
| privilege_transition_type | string | The kind of privilege-related transition analyzed, such as a credential change, capability update, namespace transition, or privileged system call. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

