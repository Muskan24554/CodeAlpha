## Exploratory Data Analysis (EDA)
## Introduction
This Excel‑based Exploratory Data Analysis profiles customer demographics and behavior to understand structure, distributions, relationships, and segment differences before modeling or dashboards, following CodeAlpha Task 2 guidance using the Analysis and standard charts

## KPIs (Key Performance Indicators)

Descriptive statistics for Age, tenure, and past_3_years_bike_related_purchases to report mean/median, dispersion, skew, and kurtosis via the ToolPak.

Correlation among numeric fields (for example, tenure and purchases) using Pearson coefficients on a contiguous numeric block with labels

Group comparisons with two‑sample t‑tests or one‑way ANOVA, where appropriate (for example, purchases by gender and Age), to confirm or reject segment differences

## Project Objective

Produce a reproducible EDA that answers defined questions, summarizes univariate distributions, explores bivariate relationships, validates at least one assumption with a simple test, and records data‑quality issues and remedies for downstream work.

Keep all outputs in labeled sheets (Questions & Dictionary, Data Quality, Univariate, Bivariate/Correlation, Hypotheses & Tests, Findings) so reviewers can trace steps.
## Dashboard
<img width="927" height="466" alt="<img width="821" height="374" alt="image" src="https://github.com/user-attachments/assets/3b6d01f1-b099-4b8a-9035-00f93cb3e1e5" />

<img width="858" height="282" alt="image" src="https://github.com/user-attachments/assets/f22dd9d5-7ebe-40ea-b36c-136fdd77ce3d" />


<img width="1456" height="554" alt="image" src="https://github.com/user-attachments/assets/f4d0fe20-0578-4569-a4d6-4d6b0feb93f4" />


<img width="1414" height="588" alt="image" src="https://github.com/user-attachments/assets/fa738a9f-eab5-4f5e-9f0b-cdde747b22ed" />

<img width="1657" height="525" alt="image" src="https://github.com/user-attachments/assets/372d5989-319c-4a3b-a916-8977e997543b" />

<img width="1047" height="535" alt="image" src="https://github.com/user-attachments/assets/040ec420-d7fa-4c2d-91ae-efae1bf01bc1" />

<img width="861" height="387" alt="image" src="https://github.com/user-attachments/assets/46ce2e15-b6e3-4006-8699-1e3964013863" />
<img width="1307" height="706" alt="image" src="https://github.com/user-attachments/assets/0c8aafe7-835d-410c-beca-85f9c1f8a224" />





## Project Insights
Gender segmentation shows 2,039 females, 1,873 male, and 88 unknown customers with average bike purchases of about 48.24, 49.91, and 42.25, respectively, motivating a two‑sample t‑test on male vs female purchase means rather than a paired test across variables.

Wealth segments exhibit similar average tenure (Affluent ≈ 10.52 years, High Net Worth ≈ 10.74, Mass Customer ≈ 10.68), implying tenure is not strongly separated by wealth status in this sample.

Pearson correlation between tenure and purchases is near zero (r ≈ =-0.0097), indicating no meaningful linear relationship at the aggregate level; subgroup analysis can check for hidden effects.

The tenure histogram is right‑skewed with a long upper tail, so reporting median and IQR alongside mean and standard deviation is recommended, and outliers should be reviewed in context.

## Skills Used
Data Cleaning & Transformation

Pivot charts and table

Excel data preparation and cleaning (de‑duplication, type standardization, categorical normalization) to ensure valid statistical inputs and interpretable outputs.

Analysis ToolPak procedures: Descriptive Statistics, Histogram, Correlation, two‑sample t‑tests, with concise interpretations tied back to the opening questions.

Structured EDA reporting with labeled sheets and brief narrative notes 

Genre & Audience Engagement Analysis

## Final Conclusion
Provides a clear foundation for visualization or modeling, with documented data‑quality actions to ensure trust in downstream decisions, and with segmentation tables, a corrected correlation matrix, a tenure distribution analysis, and at least one proper hypothesis test between groups

By using minimum vote thresholds and weighted ratings, analysts can identify genuinely well-received titles.

Stakeholders can use these insights to guide marketing, production, and curation decisions based on both engagement and critical reception.


