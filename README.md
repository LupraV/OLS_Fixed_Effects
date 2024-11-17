# Investigating the Impact of Psychological Distress on Wealth

## Abstract
This study examines the impact of psychological distress (PD) on household wealth using synthetic longitudinal data inspired by the American Panel Study of Income Dynamics (PSID). By comparing Ordinary Least Squares (OLS) with Fixed Effects (FE) models, the analysis explores the relationship between PD and wealth while controlling for socioeconomic status (SES), life events, and demographic factors. The findings reveal that PD significantly reduces wealth, with high SES individuals and those experiencing negative life events facing compounded effects. The study highlights the need to consider mental health and life events when designing policies to address wealth inequality and financial stability.

Study conducted as part of coursework for 178724 Applied Econometrics Methods (2024, Massey University)

## Key Objectives
1. Investigate the direct impact of PD on wealth using longitudinal data.
2. Evaluate how SES and negative life events influence this relationship.
3. Compare OLS and Fixed Effects models to highlight methodological insights.

## Software
- **Stata/SE 17.0**

## Data
- The synthetic dataset (based on American PSID) includes:
  - **Dependent Variables**: Net worth and financial distress.
  - **Key Independent Variable**: Psychological distress score.
  - **Control Variables**: Income, education, age, gender, employment, SES, and life events.

## Key Findings
1. **PD Impact**:
   - Psychological distress significantly reduces wealth, with an average decrease of 5.1% per unit increase in PD.
2. **Role of SES**:
   - High SES individuals experience an additional compounded effect of PD, indicating their higher stakes in wealth loss.
3. **Life Events**:
   - Negative life events (e.g., divorce, layoffs) exacerbate the impact of PD on wealth, highlighting their critical role in financial vulnerability.

## Methodology
1. **Descriptive Analysis**:
   - Summary statistics and visualizations of wealth, PD, and SES distributions.
   - Arcsinh transformations applied to wealth and SES to address skewness.
2. **OLS vs Fixed Effects**:
   - Comparison of models to account for individual-specific heterogeneity and temporal dynamics.
3. **Interaction Effects**:
   - Examines PD's interaction with SES and negative life events.

