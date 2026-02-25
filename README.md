# Hospital-Readmission-Risk-in-Diabetic-Patients-EDA-PROJECT-

## Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on hospital encounter data of diabetic patients to identify patterns influencing 30-day readmissions.

Hospital readmissions increase healthcare costs and may indicate gaps in discharge planning or post-treatment care. The objective of this analysis is to understand clinical and demographic factors associated with readmission risk and provide data-driven strategic recommendations.

### Project Objectives

Perform systematic data cleaning and preprocessing

Identify factors influencing hospital readmission

Conduct statistical hypothesis testing

Engineer meaningful risk-based features

Generate actionable healthcare insights

### Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

SciPy

Jupyter Notebook

Git & GitHub

## Key Findings

#### Hospital stay duration is significantly associated with readmission.

Patients with longer hospital stays show higher readmission risk (p < 0.001).

#### Clinical severity matters more than demographics.

Gender is not significantly associated with readmission.

#### High medication count and multiple diagnoses indicate complex cases.

These patients require enhanced discharge planning.

#### Frequent hospital visitors show higher healthcare dependency.

Preventive monitoring programs may reduce repeat admissions.

#### Readmission risk is multi-factorial.

No single predictor dominates; a composite risk scoring approach is recommended.


### Feature Engineering Highlights:

High medication flag

Long stay flag

Elderly flag

Total visits feature

High diagnosis count flag

These features support risk segmentation and predictive modeling.

### Data Quality Considerations:

Missing values in race and diagnosis fields

Placeholder values ("?") handled

Age converted from categorical ranges to numeric

No time-based column available for trend analysis


### Strategic Recommendations

Implement risk-based discharge planning for long-stay patients

Provide medication counseling for high-medication cases

Develop composite readmission risk scoring

Schedule early post-discharge follow-up for high-risk segments


### Final Processed Dataset

Available at:

data/processed/final_cleaned_day4.csv

### Conclusion

The analysis demonstrates that hospital readmission risk among diabetic patients is strongly influenced by clinical severity and healthcare utilization patterns. By leveraging data-driven insights and risk stratification strategies, healthcare institutions can proactively identify high-risk patients and reduce avoidable readmissions.
