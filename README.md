# COVID19 Symptom Checker
## About Dataset
These data will help to identify whether any person is having a coronavirus disease or not based on some pre-defined standard symptoms. These symptoms are based on guidelines given by the World Health Organization (WHO)who.int and the Ministry of Health and Family Welfare, India.

### Objective
1. Design and implement a data pipeline for pre-processing the raw dataset and clean data
2. Compare the performance of three supervised classification techniques to suggest an efficient model for predicting which patient got COVID19 through some symptoms, experiencing symptoms, severity and contact.

## Dataset overview
**Dataset:** [Link](https://www.kaggle.com/datasets/iamhungundji/covid19-symptoms-checker?fbclid=IwAR2UV3l2_Guh_fM6BEr83W0fr1gOlu4rJWDhOFDvazB0p_VP7iiyFA2BAr8&select=Raw-Data.csv)

**Describe:** The dataset contains seven major variables that will be having an impact on whether someone has coronavirus disease or not, the description of each variable are as follows,
+ Country: List of countries person visited.
+ Age: Classification of the age group for each person, based on WHO Age Group Standard
+ Symptoms: According to WHO, 5 are major symptoms of COVID-19, Fever, Tiredness, Difficulty in breathing, Dry cough, and sore throat.
+ Experience any other symptoms: Pains, Nasal Congestion, Runny Nose, Diarrhea and Other.
+ Severity: The level of severity, Mild, Moderate, Severe
+Contact: Has the person contacted some other COVID-19 Patient

+ With all these categorical variables, a combination for each label in the variable will be generated and therefore, in total 316800 combinations are created.

**Data:** 
+ Raw-Data: This file contains all the possible labels of variables, this file is used to generate the cleaned data.
+ Cleaned-Data: This file contains all possible combinations of data from Raw-Data.csv, can be used for analysis. Contains dummy variables after combination, can refer the notebook, for how this data is generated.

## Technologies
**Language:** Python

**Framework/Libary:** Python, Pandas, Numpy, Scikit-Learn

**Machine Learning Algorithms:** Logistic Regression, Decision Trees, XGBoost (Extreme Gradient Boosting)

**Metric:** Accuracy, F1-score, Precison, Recall

## Contact
**Author:** Le The Tiem






