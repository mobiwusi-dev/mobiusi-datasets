---
license: cc-by-nc-sa-4.0
task_categories:
- text-classification
language:
- en
pretty_name: Commercial Building Construction Tender Opportunity Dataset
---

# Commercial Building Construction Tender Opportunity Dataset

This dataset contains web text from commercial building construction tenders, subcontractor solicitations, and other bid opportunities, paired with structured JSON records. The records cover project packages, scope of work, bidder qualifications, key dates, submission requirements, and related opportunity details. This pairing supports training and evaluating models that extract procurement information from web pages and generate JSON according to a defined schema.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| packages | array | The lots, packages, or construction scopes listed in the notice that may be bid on separately. |
| key_dates | object | Important dates and times, such as the notice date, site visit, question deadline, and bid deadline. Preserve the format and time zone shown in the notice where possible. |
| buyer_name | string | The company, organization, or owner issuing the tender or procurement opportunity; may be an empty string if not stated. |
| overall_scope | string | A summary of the construction work, main project activities, or services covered by the notice. |
| project_title | string | The project or procurement opportunity title stated in the tender notice. |
| procurement_type | string | The type of opportunity, such as a construction tender, subcontractor solicitation, or bid opportunity. |
| project_location | object | The geographic location and detailed address information for the project. |
| source_page_html | string | The original HTML of the tender notice webpage used as the source for structured information extraction. |
| contact_information | object | Contact names and details provided for project inquiries, document access, or bid communications. |
| submission_requirements | object | Requirements for bid submission, including the submission method, delivery address, file format, and required documents. |
| eligibility_requirements | array | The qualifications, experience, licenses, and other conditions required of bidders or subcontractor applicants. |

## Compliance Statement

<table>
  <tr><td>Authorization Type</td><td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td></tr>
  <tr><td>Commercial Use</td><td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td></tr>
  <tr><td>Privacy and Anonymization</td><td>No PII, no real company names, simulated scenarios follow industry standards</td></tr>
  <tr><td>Compliance System</td><td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td></tr>
</table>


## Source & Contact

contact@mobiusi.com

