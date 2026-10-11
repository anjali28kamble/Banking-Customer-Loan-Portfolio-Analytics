# Banking Customer & Loan Portfolio Analytics

## Project Overview

This project analyzes banking loan application data to understand loan approval and rejection patterns, customer characteristics, and financial risk indicators. The goal is to transform raw data into meaningful insights that can support data-driven lending decisions.

The project follows an end-to-end data analytics workflow using Excel, Power Query, MySQL, Python, and Power BI.

## Business Problem

Banks need to understand loan application outcomes and identify patterns across customer demographics, loan purposes, credit scores, and financial indicators. Analyzing these factors can help stakeholders investigate rejection patterns, evaluate portfolio trends, and improve reporting.

## Project Objectives

- Analyze approved and rejected loan applications.
- Examine customer demographics and financial characteristics.
- Explore credit scores, debt-to-income (DTI) ratios, and other risk indicators.
- Use SQL to answer business questions.
- Perform exploratory data analysis using Python.
- Build an interactive Power BI dashboard.
- Present findings and recommendations for further business investigation.

## Dataset

- **Raw records:** 15,020
- **Cleaned records:** 15,000
- **Columns:** 26
- **Primary identifier:** `Application_ID`
- **Outcome field:** `Loan_Status`

The dataset includes application outcomes, applicant characteristics, loan purposes, income details, credit scores, and financial indicators.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Excel | Initial data inspection and preparation |
| Power Query | Data cleaning and transformation |
| MySQL | Data querying and business analysis |
| Python | Exploratory data analysis |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Power BI | Interactive dashboard development |
| DAX | Measures and KPI calculations |

## Data Cleaning

The data preparation process included:

- Inspecting missing and inconsistent values.
- Reviewing credit score and loan amount fields.
- Preparing cleaned analytical columns.
- Standardizing property area values.
- Preparing the cleaned dataset for SQL analysis and Power BI reporting.

## SQL Analysis

SQL was used to investigate business questions, including:

- What is the total number of loan applications?
- How many applications were approved and rejected?
- What are the approval and rejection rates?
- Which loan purposes have the most applications?
- How do application outcomes vary across customer and financial segments?

## Python Exploratory Data Analysis

Python and its data analysis libraries were used to explore distributions, compare application outcomes, examine financial indicators, and visualize patterns in the dataset.

## Power BI Dashboard

The Power BI report contains four pages:

1. **Loan Portfolio Overview** — application volume, approval and rejection KPIs, and loan purpose trends.
2. **Customer Analytics** — customer characteristics, income profiles, education, employment, and property area.
3. **Financial Risk Analysis** — DTI ratios, credit scores, income, debt, and loan-related indicators.
4. **Loan Decision Insights** — comparisons of loan outcomes across customer segments.

## Key Results

Based on the current Power BI dashboard:

- **Total applications:** 15,000
- **Approved applications:** 5,782
- **Rejected applications:** 9,218
- **Approval rate:** 38.55%
- **Rejection rate:** 61.45%
- **Largest loan-purpose category:** Home Purchase, with approximately 3,755 applications.

These figures describe the analyzed dataset and do not establish the reasons for loan rejection or predict future defaults.

## Business Insights & Recommendations

The analysis highlights a higher number of rejected applications than approved applications and substantial demand in the Home Purchase category.

Recommended next steps for a banking team include:

- Investigate rejection patterns across credit score, DTI, employment status, and loan purpose.
- Compare financial indicators across approved and rejected applications.
- Examine demand by loan purpose to support portfolio planning.
- Improve data validation and maintain consistent KPI definitions.
- Validate findings before using them to change lending policies.

These recommendations are proposed actions, not proof of causation.

## Limitations

- The analysis describes the available dataset and may not represent every banking customer.
- Segment-level conclusions require validation against the underlying analysis.
- The project does not establish causal relationships between customer characteristics and loan decisions.
- It is not a validated loan-default prediction model.

## Future Scope

- Automate data refresh and reporting.
- Add more detailed segment-level analysis.
- Develop additional interactive KPI measures.
- Explore predictive modeling if suitable target labels and validation data are available.
- Improve data quality checks and reporting documentation.

## Project Deliverables

- Cleaned dataset
- MySQL business analysis queries
- Python EDA notebook
- Power BI dashboard
- Dashboard PDF export
- Project report

## Conclusion

This project demonstrates an end-to-end data analytics workflow, from data preparation and SQL analysis to Python exploration, Power BI visualization, and business recommendations. It showcases practical skills in data cleaning, querying, analysis, dashboard development, and communicating findings.


---

**Author:** Anjali Kamble

**Focus:** Data Analytics | SQL | Python | Power BI | Excel
