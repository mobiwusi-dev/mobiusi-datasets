---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: UAV Photogrammetry Reconstruction Defect Root-Cause Question-Answer Dataset
---

# UAV Photogrammetry Reconstruction Defect Root-Cause Question-Answer Dataset

This question-answer dataset describes quality defects in UAV photogrammetry reconstruction outputs alongside relevant inspection clues. It covers common issues such as local model bulging, ghosting, holes, and blurred edges; answers use the clues to infer possible acquisition or processing causes and explain the supporting evidence. The dataset supports defect diagnosis and root-cause reasoning for engineering surveying deliverables, quality inspection, acceptance, and technical support.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| case_prompt | string | The original text describing the photogrammetry defect and any related quality inspection clues. |
| probable_causes | array | Likely data acquisition or processing causes inferred from the defect and inspection clues. |
| assistant_answer | string | The final user-facing answer combining the diagnosis, likely causes, and supporting evidence. |
| diagnosed_defect | string | The defect identified from the case prompt, such as local bulging, ghosting, holes, or blurred edges. |
| evidence_reasoning | string | An explanation connecting the inspection clues to the diagnosed defect and probable causes. |
| recommended_checks | string | Suggested follow-up checks or actions to validate the diagnosis or address the likely causes. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

