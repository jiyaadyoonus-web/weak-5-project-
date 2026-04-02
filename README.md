Healthcare Analytics System (Synthetic Data)
Exploratory Data Analysis (EDA) Project

Overview

This project focuses on analyzing patient health data using a synthetically generated dataset. Healthcare institutions generate vast amounts of patient information, but manual analysis is inefficient, time-consuming, and prone to errors. Due to privacy concerns, real-world patient datasets are often unavailable for academic use. Therefore, this project simulates realistic healthcare data and applies data analysis techniques to extract meaningful insights.

The workflow includes:

Synthetic data generation using Python
Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Risk classification of patients
Data visualization
Insight generation
The objective is to build a structured and scalable analytics system that can help in identifying high-risk patients and supporting healthcare decision-making.

Dataset

Source: Synthetic (Randomly Generated Dataset using Python & Faker)

Description:

The dataset contains 10,000 patient records with the following attributes:

Column Name: Description
Patient_ID: Unique identifier
Age: 20–80
Gender: Male / Female
Blood_Pressure: 80–180
Sugar_Level: 70–200
Cholesterol: 150–300
Heart_Rate: 60–120

Objectives

Generate a realistic synthetic healthcare dataset
Perform data cleaning and preprocessing
Compute statistical measures (mean, median, standard deviation)
Analyze key health parameters:
oBlood pressure
oSugar levels
oCholesterol
oHeart rate
Classify patients into risk levels (Low, Medium, High)
Identify high-risk patients for early intervention
Perform group-based analysis:
oAge group vs health condition
oGender-wise comparison
oRisk distribution
Study relationships between variables:
oBlood pressure vs age
oCholesterol vs heart rate
oSugar level vs risk
Visualize data using multiple charts
Derive actionable healthcare insights

Project Highlights

1. Data Preprocessing

Checked for missing values and ensured data consistency
Generated clean and structured dataset
Created additional features:
oRisk Level (Low / Medium / High)
oAge Groups (Young, Adult, Mid-Age, Senior)

2. Exploratory Data Analysis (EDA)

Analyzed distributions using histograms
Studied relationships using scatter plots
Used box plots to detect outliers
Evaluated correlations using heatmaps

3. Risk Classification

Patients were classified based on medical thresholds:

Low Risk: Normal health parameters
Medium Risk: Moderate abnormalities
High Risk: Multiple abnormal conditions
Criteria included:
High blood pressure
High sugar levels
High cholesterol
Elevated heart rate

4. Group-Based Analysis

Age Group Analysis: Older patients tend to show higher risk
Gender Analysis: Compared average health metrics across genders
Risk Distribution: Identified proportion of patients in each risk category

5. Visualization

The project includes the following visualizations:

Bar charts (Age group vs Risk level)
Pie charts (Risk distribution)
Histograms (Health parameter distributions)
Scatter plots (Age vs Blood Pressure)
Box plots (Outlier detection)
Heatmaps (Correlation analysis)

Tools and Technologies

Python
pandas
numpy
matplotlib
seaborn
Faker (for synthetic data generation)
Jupyter Notebook

Results

Key Findings

Blood pressure tends to increase with age
High sugar and cholesterol significantly contribute to higher risk levels
A portion of patients fall into the high-risk category requiring attention
Strong relationships exist between multiple health parameters
Outliers were identified in several health metrics

Interpretation

Risk Identification: The system effectively identifies high-risk patients
Preventive Insight: Early detection helps reduce serious health complications
Correlation Strength: Health parameters are interrelated
Data Simulation Value: Synthetic data is useful for academic and research purposes

Conclusion

This project demonstrates how synthetic healthcare data combined with EDA techniques can be used to analyze patient health effectively.

The structured workflow improves:

Data understanding
Risk detection
Healthcare decision-making
This system can be extended to real-world datasets for better patient monitoring and predictive analytics.
name : yoonus arafaath 
