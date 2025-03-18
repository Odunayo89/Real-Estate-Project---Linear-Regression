# Real-Estate-Project---Linear-Regression
Dataset Description for GitHub:
Dataset Name: Real Estate Sales (2001-2022)

Description:
This dataset contains real estate sales data from 2001 to 2022, including information about property sales, assessed values, sales ratios, property types, and other relevant details.

File Format: CSV

Number of Rows: 1,048,575
Number of Columns: 14

Column Details:

Serial Number - Unique identifier for each sale record.
List Year - The year the property was listed for sale.
Date Recorded - The date when the sale was recorded.
Town - The town where the property is located.
Address - The specific address of the property.
Assessed Value - The official assessed value of the property.
Sale Amount - The actual sale price of the property.
Sales Ratio - The ratio of the assessed value to the sale amount.
Property Type - The category of the property (Residential, Commercial, etc.).
Residential Type - More specific classification of residential properties (Single Family, Two Family, etc.).
Non Use Code - Code indicating if the sale was not used for valuation purposes.
Assessor Remarks - Comments or notes from the property assessor.
OPM Remarks - Additional remarks from the Office of Policy and Management.
Location - Geographical coordinates (longitude, latitude) of the property.
Data Insights:

The dataset includes over 1 million real estate transactions.
There are missing values in some columns, such as "Property Type," "Residential Type," "Non Use Code," "Assessor Remarks," and "OPM Remarks."
The "Sales Ratio" column has a wide range, with some extreme values.


**##Baseline Model: Linear Regression**

As part of the modeling workflow, I started with Linear Regression to establish a baseline for predicting Sale Amount based on property features and location.
🎯 Why Linear Regression?
Linear Regression is often used as a starting point to understand how well a linear relationship explains the variation in the target variable.
It is simple, interpretable, and useful for benchmarking.
📉 Observations:
The model achieved an R² of ~0.20, indicating that only ~20% of the variance in the sale amount is explained by the features provided.
From exploratory data analysis (EDA), there were signs of non-linearity and complex interactions between variables (e.g., Town, Residential Type), suggesting that Linear Regression might not fully capture the underlying patterns.
🧠 What’s next?
I will apply non-linear and ensemble models, such as Random Forest and potentially XGBoost, to better capture the complex relationships in this dataset.
The performance of these models will be compared against this baseline.
