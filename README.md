# HealthCareAnalysis
Healtcare analysis of a healthcare dataset

This project focuses on analyzing healthcare data to provide insights into treatment costs, high-risk patients, and billing patterns. The dataset is assumed to contain key columns such as medical conditions, age, admission type, billing amount, and test results, and the analysis is conducted using pandas, seaborn, and matplotlib for data processing and visualization.

Functions
1. Average Treatment Cost by Disease
This function calculates the average treatment cost for each medical condition (disease) by grouping the data by Medical Condition and calculating the mean of Billing Amount.

2. Identifying High-Risk Patients
This function identifies high-risk patients based on the medical condition, age, admission type, and test results.
It filters the dataset to find patients over a certain age threshold with abnormal test results and who were admitted via emergency.

4. Analyze Billing by Insurance Provider
This function calculates the average billing amount for each insurance provider and displays a bar plot showing the differences between them.





