# Liberty Exports Global Trade Intelligence: SPSS Reporting Project

A concise SPSS reporting portfolio based on trade intelligence records, contact readiness, lead priority and business follow-up readiness.

## Project Overview

This project uses a structured trade intelligence dataset for Liberty Exports to show how raw Excel and CSV records can be prepared for SPSS, checked for data quality and summarised into practical reporting outputs.

The work focuses on data cleaning, records validation, contact readiness, lead prioritisation and decision-support reporting. It is a descriptive business reporting project rather than a predictive modelling or machine learning project.

## Business Question

The analysis was designed around a practical reporting question: which business records are clean, complete and ready enough to support follow-up planning?

- Which records have enough contact and source information for follow-up?
- Which business categories show stronger lead priority?
- How is the dataset distributed by category and state or coverage area?
- What data quality gaps should be reviewed before outreach or management action?

## Dataset Description

The SPSS-ready dataset contains 1,252 trade intelligence records across suppliers, freight and customs agents, logistics providers, market shops and buyers, wholesale markets, institutional bodies, events and trade regulation records.

| Field Group | Examples | Reporting Purpose |
| --- | --- | --- |
| Business record information | sheet_type, company_name, organisation_type, state, city | Used to understand record category, location coverage and business context. |
| Contact and source fields | email, phone, website, source_link, source_type | Used to assess whether records are ready for business follow-up. |
| Reporting indicators | has_email, has_phone, has_website, has_source, contact_completeness_score | Used to summarise contact completeness and records validation status. |
| Priority and quality indicators | importance, importance_num, lead_score, data_quality_flag | Used to identify high-priority records and data quality gaps. |

## Tools Used

- Excel and CSV for structured record preparation
- SPSS for frequency tables, descriptive summaries and visual reporting
- HTML for a browser-ready portfolio report

## Data Preparation

- Standardised trade intelligence records into an SPSS-ready CSV file.
- Created contact availability indicators for email, phone, website and source link fields.
- Prepared contact completeness, lead priority and data quality reporting fields.
- Checked records for practical reporting use and follow-up readiness.

## SPSS Analysis Workflow

1. Import the cleaned CSV file into SPSS.
2. Review data quality and contact availability fields.
3. Create summary reporting groups for contact readiness, lead priority and business follow-up readiness.
4. Generate short summary tables and SPSS charts.
5. Export the selected SPSS Output Viewer charts for portfolio reporting.

## Key Charts and Findings

### Data Quality Status

![Data Quality Status of Business Records](assets/spss_charts/data_quality_status.png)

Most records are classified as Partial, showing that the dataset is useful for reporting but still requires validation before direct outreach.

### Contact Readiness

![Contact Readiness for Business Follow-up](assets/spss_charts/contact_readiness.png)

Most records sit in the partial readiness group, which indicates that follow-up planning should include an additional contact checking step.

### Business Follow-up Readiness

![Records Ready for Business Follow-up](assets/spss_charts/business_followup_readiness.png)

This chart separates records that are ready for follow-up from records that need further data review.

### Lead Priority

![Lead Priority Groups for Business Follow-up](assets/spss_charts/lead_priority_groups.png)

The high-priority group provides a practical shortlist for reviewing records before outreach or management action.

### Contact Information Availability

![Contact Information Availability Across Records](assets/spss_charts/contact_information_availability.png)

Website and source information are more consistently available than direct email and phone details, which explains why many records require follow-up validation.

### Business Category Distribution

![Business Record Distribution by Category](assets/spss_charts/business_category_distribution.png)

The dataset is concentrated in suppliers, freight and customs agents, logistics, and market shop or buyer records.

### State or Coverage Area Distribution

![Business Record Distribution by State or Coverage Area](assets/spss_charts/state_distribution.png)

Australia-wide and South Australian records form a large share of the dataset, with additional coverage across NSW, VIC, QLD and WA.

### High-Priority Records by Category

![High-Priority Records by Business Category](assets/spss_charts/high_priority_by_category.png)

High-priority records are concentrated in suppliers, freight and customs agents, and market shop or buyer categories.

## Management Recommendations

- Use high-priority supplier and freight records as the first review group for business follow-up planning.
- Validate email and phone details before direct outreach because these fields are less complete than website and source information.
- Use contact readiness as a screening step before assigning records for action.
- Continue enriching partial records so that the dataset can support more reliable reporting and stakeholder follow-up.

## Skills Demonstrated

- Preparing Excel and CSV records for SPSS reporting
- Checking data quality and contact completeness
- Validating business records for follow-up readiness
- Producing SPSS charts and summary reporting outputs
- Turning record-level data into practical decision-support reporting

This report uses selected SPSS-generated chart images and avoids command logs, technical run output, duplicate charts and long technical tables.
