# Healthcare Intelligence: Operational, Financial and Procedure Analysis
## Project Overview

This project analyses historical healthcare datasets to generate insights into hospital operations, financial performance, payer coverage and procedure utilisation.

The analysis transforms healthcare records into an interactive Power BI dashboard to support evidence-based decision-making and healthcare resource planning.

## Project Objectives

1. Assess the quality and reliability of the available healthcare datasets.
2. Analyse encounter volumes, encounter classes and encounter durations.
3. Evaluate claim costs and payer coverage patterns.
4. Identify frequently performed and high-cost procedures.
5. Develop an interactive dashboard to communicate findings and recommendations.

## Tools and Technologies

- **Power BI:** Dashboard development and data visualisation.
- **Power Query:** Data preparation, transformation and quality checks.
- **DAX:** Measures and calculated columns for analytical KPIs.
- **Microsoft Excel:** KPI documentation and validation evidence.

## Dashboard Structure

### 1. Hospital Operations

Examines:
- Total healthcare encounters.
- Annual encounter trends.
- Encounter distribution by class.
- Encounters lasting longer than 24 hours.

### 2. Financial Intelligence

Examines:
- Total claim costs.
- Average claim costs.
- Total payer coverage.
- Encounters with zero recorded payer coverage.
- Average claim costs by payer category.

### 3. Procedure Intelligence

Examines:
- Most frequently recorded procedures.
- Average procedure costs.
- Relationship between procedure frequency and average cost.

## Selected Findings

- Ambulatory encounters represented the largest share of recorded encounters.
- Inpatient encounters had the highest count of encounters lasting longer than 24 hours among the encounter classes analysed.
- Approximately 0.27% of encounters with valid duration records exceeded 24 hours.
- Total recorded payer coverage was approximately 31.1 million.
- Approximately 14,000 encounters had zero recorded payer coverage.
- Medicaid recorded the highest average claim cost among the payer categories analysed.
- Assessment of Health and Social Care was the most frequently recorded procedure.
- Admit to ICU (Procedure) had the highest average procedure cost among the top 10 procedures analysed.
- No clear relationship was observed between procedure frequency and average procedure cost.

## Data Quality and Validation

Data-quality checks covered:
- Missing values and duplicate identifiers.
- Referential integrity across related datasets.
- Invalid and negative financial values.
- Encounter duration validity.
- Procedure record completeness.

Supporting documentation is included in the Data Quality and Validation folders.

## Key Recommendations

1. Investigate encounters with zero recorded payer coverage.
2. Monitor inpatient encounter duration and patient flow.
3. Review high-cost procedures to support expenditure planning.
4. Align staffing and resources with frequently performed procedures.
5. Strengthen financial monitoring across payer categories and encounter classes.

## Project Deliverables

The project folder contains:

- Power BI dashboard file (`.pbix`).
- Dashboard PDF export.
- Data quality assessment.
- KPI definition sheet.
- Validation evidence.
- Executive summary.
- Dashboard screenshots.

## Limitations

- Zero recorded payer coverage does not necessarily establish that a patient paid out of pocket.
- Average costs and total costs measure different aspects of expenditure.
- Procedure frequency counts recorded procedure records, not necessarily unique patients.
- The analysis identifies patterns and associations; it does not establish causal relationships.
- Findings depend on the completeness and accuracy of the supplied historical data.

## Conclusion

The project demonstrates the use of data preparation, analytical calculations and interactive visualisation to transform healthcare datasets into actionable operational, financial and procedural insights.

The resulting dashboard provides a foundation for healthcare performance monitoring and further investigation.

