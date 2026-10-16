---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Korean Public Notice Comprehension Dataset for Learners
---

# Korean Public Notice Comprehension Dataset for Learners

Contains structured JSON samples based on Korean public documents, including announcements, service notices, waste-sorting guides, traffic advisories, event notices, and administrative instructions. Each sample identifies the notice category, key points, intended audience, schedule, location, restrictions, required actions, and contact information, with a learner-friendly Chinese summary and additional explanations. The collection supports Korean document understanding, key information extraction, and public-service information interpretation for language learners.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| location | object | Locations, addresses, and relevant arrival or transportation guidance stated in the notice. |
| schedule | object | Dates, time periods, deadlines, or implementation times stated in the notice. |
| key_matters | object | The topic, core content, and importance of the notice extracted from the source text. |
| restrictions | array | Prohibitions, eligibility criteria, quantity or age limits, document requirements, and other conditions that must be met. |
| learner_summary | string | A concise Chinese summary of the notice requirements, applicable scope, and most important actions, written to help Korean learners understand it quickly. |
| notice_category | string | The category of the public document, inferred from its content. |
| required_actions | array | Clear, actionable steps that readers are instructed to take. |
| source_notice_text | string | The Korean source text of a public notice, service instruction, waste-sorting guide, traffic advisory, event announcement, or administrative explanation to be understood and parsed. |
| applicable_audience | array | The people or groups explicitly covered by the notice or expected to follow its requirements, such as residents, visitors, passengers, or other affected parties. |
| contact_information | object | The issuing organization and any listed phone numbers, websites, inquiry channels, or consultation hours. |
| learner_explanation | string | Explanations for Korean learners covering potentially confusing vocabulary, institutional context, polite expressions, or practical points to note when completing a procedure. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

