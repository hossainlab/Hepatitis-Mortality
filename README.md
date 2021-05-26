# Hepatitis Mortality Prediction using Machine Learning 

## Introduction 
Hepatitis is a term that refers to liver inflammation. The liver is a vital organ responsible for nutrient processing, blood filtering, and infection defense. When the liver becomes inflamed or damaged, it can lose its function. Hepatitis can be caused by excessive alcohol consumption, toxins, certain medications, and certain medical conditions.

*Source:https://www.cdc.gov/hepatitis/*

## Objective(s)
- Predict if a patient will live or die based on the parameters using Machine Learning Algorithms. 


## Dataset Information
     1. Class: DIE, LIVE
     2. AGE: 10, 20, 30, 40, 50, 60, 70, 80
     3. SEX: male, female
     4. STEROID: no, yes
     5. ANTIVIRALS: no, yes
     6. FATIGUE: no, yes
     7. MALAISE: no, yes
     8. ANOREXIA: no, yes
     9. LIVER BIG: no, yes
    10. LIVER FIRM: no, yes
    11. SPLEEN PALPABLE: no, yes
    12. SPIDERS: no, yes
    13. ASCITES: no, yes
    14. VARICES: no, yes
    15. BILIRUBIN: 0.39, 0.80, 1.20, 2.00, 3.00, 4.00
        -- see the note below
    16. ALK PHOSPHATE: 33, 80, 120, 160, 200, 250
    17. SGOT: 13, 100, 200, 300, 400, 500, 
    18. ALBUMIN: 2.1, 3.0, 3.8, 4.5, 5.0, 6.0
    19. PROTIME: 10, 20, 30, 40, 50, 60, 70, 80, 90
    20. HISTOLOGY: no, yes

    
*Data Source:* https://archive.ics.uci.edu/ml/machine-learning-databases/hepatitis/


## Data Analysis Workflow
- [] Data Collection
- Importing Data
- Data Cleaning
  - Handling Missing Data
  - Outlier Detection and Removal
- Exploring Data using Descriptive Statistics
  - Understanding Data using
    - Univariate Analysis
    - Bivariate Analysis
    - Multivariate Analysis
  - Understanding Data using Visualizations
    - Univariate
      - Histograms
      - Density Plot
    - Bivariate
      - Scatter Plot
      - Boxplot
    - Multivariate
      - Correlation Matrix
      - Covariance Matrix
- Decision Making using Inferential Statistics
  - Hypothesis Testing(T-Test, Z-Test, Chi-square, ANOVA)
  - Creating Predicting Models