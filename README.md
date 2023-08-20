# Automation-of-Duty-plan
Automation of Standby Duty Planning for Rescue Drivers via a Forecasting Model
Problem Statement:
 The problem at hand is to develop a predictive model that maximizes the number of activated standby-drivers while minimizing the occurrence of having insufficient standbys available. The goal is to optimize resource allocation and ensure prompt response to emergency situations.
Project Objectives:
1.	Develop an accurate predictive model that forecasts the required number of standby-drivers based on historical data and relevant factors.
2.	Maximize the utilization of standby-drivers by minimizing instances where there are inadequate standbys available.
3.	Provide actionable insights and recommendations to improve resource allocation and emergency response efficiency.
Dependencies:
1. pandas 
2. numpy 
3. matplotlib
4. seaborn
Project Files:
data_exploration: This is where the initial data analysis is done, where the quality of the provided dataset is assessed and findings are visualized.
data_preprocessing:This covers the data preprocessing steps, such as handling missing values, feature engineering, and preparing the dataset for modeling.
baseline_model: this implements the baseline model, which is a simple approach like using a fixed number of standby drivers or a basic forecasting method.
predictive_model: It focuses on developing an accurate predictive model that fulfills the business requirements, maximizing the activated standby drivers while minimizing instances of insufficient standby availability.
Data:
 sickness_table.csv contains the daily information on sickness counts, emergency calls, available standby resources, and additional driver requirements.
