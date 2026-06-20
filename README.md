# Taxi-Revenue-Optimization-Analysis
Taxi Revenue Optimization Analysis

Project Overview
This project analyzes NYC Taxi trip data to uncover business insights that can help maximize driver revenue and improve operational efficiency.
The analysis focuses on customer payment behavior, trip characteristics, fare patterns, and statistical hypothesis testing to identify factors influencing taxi revenue.

Business Problem
Taxi companies aim to maximize revenue while maintaining a positive customer experience.
This project investigates whether payment methods influence fare amounts and whether encouraging specific payment types can increase driver earnings.

Key business questions include:
Do card users spend more than cash users?
Which payment method generates higher revenue?
How does passenger count impact fares?
Are there significant differences in customer behavior based on payment type?

Dataset
Taxi Trip Records Dataset
Relevant Features:
passenger_count
payment_type
fare_amount
trip_distance
pickup_datetime
dropoff_datetime
trip_duration
vendor_id
Project Objectives
Data Cleaning
Removed invalid records
Handled missing values
Corrected data types
Created trip duration feature
Exploratory Data Analysis
Payment Type Analysis
Fare Distribution Analysis
Passenger Count Analysis
Trip Distance Analysis
Statistical Analysis

Performed Independent T-Test:
Null Hypothesis (H₀)
There is no difference in average fare between customers paying by card and cash.
Alternative Hypothesis (H₁)
There is a significant difference in average fare between customers paying by card and cash.

Result:
T-statistic = 165.5
P-value < 0.05

Conclusion:
Reject the null hypothesis.
There is a statistically significant difference in fare amount between card and cash users.

Key Findings

Payment         Preferences
Card Payments:    67.5%
Cash Payments:    32.5%
Customers strongly prefer card payments.

Average Fare
Payment Type	Average Fare
Card          	13.7
Cash	          12.25
Card users generate higher revenue.

Trip Distance
Payment Type	Average Distance
Card	          3.23 Miles
Cash	          2.80 Miles
Card users generally take longer trips.

Business Recommendations
Encourage card payments through incentives.
Improve digital payment experience.
Provide promotional offers for card transactions.
Educate drivers on revenue benefits of digital payments.

These recommendations can help increase driver earnings and overall business revenue.

Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Jupyter Notebook
SQL

Project Deliverables
Data Cleaning Notebook
Statistical Analysis
Visualizations
Business Insights
Executive Presentation
Final Report

Future Improvements
Predictive Revenue Modeling
Customer Segmentation
Driver Performance Analysis
Dynamic Pricing Strategy
