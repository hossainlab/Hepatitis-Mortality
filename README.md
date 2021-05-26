# Heart Disease Analysis and Prediction Using Machine Learning 

## Introduction 
Heart disease describes a range of conditions that affect your heart. Diseases under the heart disease umbrella include blood vessel diseases, such as coronary artery disease; heart rhythm problems (arrhythmia); and heart defects you're born with (congenital heart defects), among others.
The term "heart disease" is often used interchangeably with the term "cardiovascular disease."Cardiovascular disease refers to conditions characterized by narrowed or blocked blood vessels, which can result in a heart attack, chest pain (angina), or stroke. Other heart conditions, such as those affecting your heart's muscle, valves, or rhythm, are also classified as heart disease. any types of heart disease can be avoided or treated by adopting a healthy lifestyle.

*Source:https://www.cdc.gov/heartdisease/about.htm*

## Symptoms 

- Chest pain, chest tightness, chest pressure and chest discomfort (angina)
- Shortness of breath
- Pain, numbness, weakness or coldness in your legs or arms if the blood vessels in those parts of your body are narrowed
- Pain in the neck, jaw, throat, upper abdomen or back

*Source:* https://www.cdc.gov/heartdisease/risk_factors.htm

## Objective(s)
- With the dataset provided for heart analysis, we have to analyse the possibilities of heart attack on the basis of various features, and then the prediction from the analysis will tell us that whether an individual is prone to heart attack or not.
- The detailed analysis can proceed with the exploratory data analysis (EDA).
- The classification for predication can be done using various machine learning model algorithms, choose the best suited model for heart attack analysis and finally save the model in the pickle (.pkl) file.

## Research Question(s)
- Does the age of a person contribute towards heart attack?
- Are different types of chest pain related to each other or the possibility of getting a heart attack?
- Does high blood pressure increase the risk of heart attack?
- Does the cholesterol level eventually contribute as a risk factor towards heart attack?



## Dataset Information
- Age : Age of the patient
- Sex : Sex of the patient
- exang: exercise induced angina (1 = yes; 0 = no)
- ca: number of major vessels (0-3)
- cp : Chest Pain type 
    - Value 1: typical angina
    - Value 2: atypical angina
    - Value 3: non-anginal pain
    - Value 4: asymptomatic
- trtbps : resting blood pressure (in mm Hg)
- chol : cholestoral in mg/dl fetched via BMI sensor
- fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- rest_ecg : resting electrocardiographic results
    - Value 0: normal
    - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- thalach : maximum heart rate achieved
- target :
    - 0 = less chance of heart attack
    - 1 = more chance of heart attack

*Data Source:* https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset


## Data Analysis Workflow
- Data Collection
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