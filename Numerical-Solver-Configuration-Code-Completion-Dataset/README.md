---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Numerical Solver Configuration Code Completion Dataset
---

# Numerical Solver Configuration Code Completion Dataset

Designed for physics and engineering simulation scripts, this dataset covers solver types, time steps and end times, iteration limits, convergence tolerances, linear and nonlinear solvers, and preconditioner settings. Each sample centers on an existing script context and its corresponding code completion, with key solver parameters provided as structured fields to help models learn context-aware numerical configuration. It supports code completion training, simulation script development, and evaluation of solver configuration generation.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| end_time | number | The termination time configured for a transient simulation. |
| time_step | number | The time step configured for time integration or transient simulation. |
| solver_type | string | The solver type configured in the completion, such as a direct solver, iterative solver, or Newton solver. |
| input_context | string | An existing simulation script snippet provided as context for model completion. |
| linear_solver | string | The solver or algorithm configuration used for linear subproblems. |
| max_iterations | integer | The maximum number of iterations allowed for the solver or nonlinear iteration process. |
| preconditioner | string | The preconditioning method configured for iterative linear solving; may be left empty when none is configured. |
| completion_code | string | The solver configuration code snippet generated to complete the input script context. |
| nonlinear_solver | string | The solver or iterative algorithm configuration used for nonlinear problems. |
| absolute_tolerance | number | The absolute error tolerance used to determine solver convergence. |
| relative_tolerance | number | The relative error tolerance used to determine solver convergence. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

