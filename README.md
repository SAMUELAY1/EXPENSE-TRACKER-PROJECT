# EXPENSE-TRACKER-PROJECT
Data-driven expense tracking and financial behavior segmentation using Python, Pandas, and Scikit-learn.

Personal Expense Tracker — Data Analysis & Clustering Project
## Overview
This project is a Personal Expense Tracker and Financial Behavior Analyzer built using Python.
It explores spending and saving patterns using data-driven insights and K-Means clustering to segment individuals into behavioral financial profiles such as “Efficient Saver”, “Balanced Spender”, and “Overspender.”
 
## Project Objectives
•	Analyze personal income and expenses data.
•	Derive financial ratios (savings rate, expense rate, spending efficiency).
•	Cluster users by financial behavior using K-Means clustering.
•	Generate actionable insights and visualizations to improve money management.
 
## Key Features
 Data Cleaning & Preparation – handle missing values, compute derived metrics
Exploratory Data Analysis (EDA) – visualize income, expenses, and savings trends
 Feature Engineering – create behavior-based ratios
 K-Means Clustering – segment users by financial patterns
 Insight Generation – recommend budgeting improvements
 Data Visualization – bar plots, scatter plots, and heatmaps using Matplotlib & Seaborn
 
## Dataset
The dataset (data.csv) contains simulated personal financial data with features such as:
Column	Description
Income	Monthly income of the user
Total_Expenses	Total monthly expenses
Savings	Remaining balance after expenses
Age, Occupation, City_Tier	 Demographic information
Potential_Savings_*	Simulated potential savings categories
 
## Tech Stack
Tool / Library	Purpose
Python (3.x)	Main programming language
Pandas, NumPy	Data manipulation
Matplotlib, Seaborn	Data visualization
Scikit-learn	Clustering (K-Means)
Jupyter Notebook 	Interactive environment
 
## Project Workflow
Data Cleaning & Preparation
•	Load dataset (PANDAS)
•	Handle missing values
•	Create Savings = Income - Total_Expenses
Exploratory Data Analysis (EDA)
•	Visualize income and expense distributions
•	Explore correlations using heatmaps
•	Identify high vs. low spenders
Feature Engineering
•	Create behavioral metrics:
•	df["Savings_Rate"] = df["Savings"] / df["Income"]
•	df["Expense_Rate"] = df["Total_Expenses"] / df["Income"]
•	df["Expense_to_Savings_Ratio"] = df["Total_Expenses"] / (df["Savings"] + 1)
## Clustering
•	Use K-Means to group users based on behavior
•	Evaluate optimal clusters using the Elbow Method
•	Label clusters as “Efficient Saver”, “Balanced Spender”, “Overspender”
Visualization & Insights
•	Plot clusters with Seaborn
•	Summarize cluster characteristics
•	Provide personalized financial insights
 
## Example Insights
Cluster	Income	Expenses	Savings Rate	Insight
0	Low	High	<20%	 Overspender — needs budgeting improvements
1	Medium	Balanced	25–35%	 Balanced spender — moderate efficiency
2	High	Moderate	>40%	Efficient saver — good financial discipline
 
## Future Improvements
•	Add interactive dashboards (Streamlit or Dash)
•	Build a predictive model for monthly savings
•	Add personalized budgeting recommendations
•	Integrate real-time expense tracking via APIs

##License

This project is licensed under the MIT License — feel free to use or modify for learning or research.

<img width="468" height="633" alt="image" src="https://github.com/user-attachments/assets/036553c6-6517-4287-b74b-90e27954616d" />
