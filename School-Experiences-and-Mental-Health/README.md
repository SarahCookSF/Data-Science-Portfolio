# School Experiences and Student Mental Health

### An Analysis of the 2025 National Youth Risk Behavior Survey (YRBS)

## Project Overview

This project explores relationships between students' experiences at school and their mental health using data from the CDC's 2025 National Youth Risk Behavior Survey (YRBS).

The analysis examines how school connectedness, bullying, and safety-related school absences are associated with students' reports of persistent sadness or hopelessness and poor mental health.

## Tools and Methods

- **Python:** pandas, matplotlib, seaborn, SciPy
- **Data preparation:** Variable selection, missing-data assessment, and response recoding
- **Exploratory analysis:** Frequency distributions, cross-tabulations, and data visualization
- **Statistical analysis:** Chi-square tests of independence and Spearman's rank correlation

## Key Findings

- **Bullying:** 58.8% of students reporting in-person bullying also reported persistent sadness or hopelessness, compared with 29.2% of students who did not report bullying.
- **School connectedness:** 14.8% of students who strongly agreed that they felt close to people at school reported frequent poor mental health, compared with 42.0% of those who strongly disagreed.
- **School safety:** 36.3% of students who missed school due to safety concerns reported frequent poor mental health, compared with 21.4% of those who did not.

## Limitations

Analyses use unweighted survey responses and do not account for the YRBS complex sampling design. Results should therefore be interpreted as exploratory associations among surveyed students, rather than nationally representative estimates. The cross-sectional data also do not establish causation.

## Data Source

Centers for Disease Control and Prevention (CDC), 2025 National Youth Risk Behavior Survey (YRBS).

## Project Files

- `school-and-mental-health.ipynb` — Jupyter notebook containing the analysis, visualizations, and statistical tests.
- `2025_national_YRBS_parsed.csv` — Dataset used for analysis.
