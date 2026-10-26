---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Botnet Infrastructure and Activity Association Analysis Q&A Dataset
---

# Botnet Infrastructure and Activity Association Analysis Q&A Dataset

This dataset focuses on infrastructure clues in threat reports, including domains, IP addresses, hosting environments, and network services, paired with analytical questions and evidence-based explanatory answers about their links to botnet activity. Its content emphasizes evidence synthesis, calibrated assessment of association strength, and attribution limitations, teaching models to distinguish direct reporting from analytical inference rather than treating a single indicator as conclusive attribution. It supports cyber threat intelligence analysis, security operations, and domain-specific supervised fine-tuning; sample counts and other dataset size details are not provided.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| answer | string | A detailed, evidence-grounded answer that synthesizes infrastructure clues and campaign context, assesses the strength of the association, and avoids treating an individual indicator as conclusive attribution. |
| question | string | An analytical question about how infrastructure clues relate to a botnet campaign or its activity. |
| campaign_assessment | string | A calibrated assessment of the relationship between the infrastructure and botnet activity, distinguishing direct reporting from analytical inference. |
| defensive_relevance | string | Defensive investigation and monitoring considerations that follow from the assessment without overstating certainty. |
| supporting_evidence | string | Observations and analytical reasoning that support or weaken a connection between the infrastructure and the suspected botnet campaign. |
| infrastructure_clues | string | Relevant infrastructure indicators and their reported or inferred roles, such as domains, IP addresses, hosting, or network services. |
| source_report_excerpt | string | The threat report passage or source material used as evidence for the analysis. |
| attribution_limitations | string | Caveats, alternative explanations, data gaps, and other constraints that prevent infrastructure clues from proving campaign ownership or attribution on their own. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

