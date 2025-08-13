# Randomized Controlled Trial (RCT) Analysis

## Project Overview
This project analyzes a randomized controlled trial dataset to explore the effects of three interventions (Placebo, Drug A, Drug B) on patients’ blood pressure, BMI, and fasting blood glucose (FBG). The dataset contains both continuous and categorical variables:

- **Continuous:** Age, BMI, Base_SBP, Base_DBP, SBP, DBP, SBP_diff, DBP_diff, FBG  
- **Categorical:** Gender, Intervention

The analysis was performed in **R and Python**, providing descriptive statistics, visualizations, and statistical tests.

---

## Data Import and Exploration

1. **Import CSV File**
```r
RCT <- read_csv("C:/Users/alreada/Desktop/El futuro/DATASETs/RCT.csv")
# RCT-Analysis
