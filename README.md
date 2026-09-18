# E-Commerce Marketing Campaign Performance Analysis and Sales Revenue Optimization

A Data-Driven Analysis of Marketing Campaign Performance and Sales Revenue

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Description

This project analyzes an E-Commerce Marketing & Sales Revenue dataset containing 18,000 records and 17 original attributes. The main purpose of the project is to understand marketing campaign performance, identify factors associated with sales revenue, compare different marketing channels and customer segments, and generate useful business insights.

The analysis was performed using Python, Pandas, NumPy, Matplotlib, and Seaborn in Jupyter Notebook.

## Objectives

The main objectives of this project are to:

- Analyze e-commerce marketing campaign performance
- Identify factors associated with sales revenue
- Compare the performance of different marketing channels
- Analyze customer segments and regional differences
- Study relationships between marketing variables and sales revenue
- Identify important patterns and trends in the dataset
- Generate data-driven business insights and recommendations

## Dataset

The dataset contains information about:

- Date and region
- Marketing channel
- Product category
- Customer segment
- Advertising spend
- Product price
- Discount rate
- Market reach
- Impressions
- Click-through rate
- Competition index
- Seasonality index
- Campaign duration
- Customer lifetime value
- Sales revenue

The dataset was obtained from Kaggle and contains 18,000 records.

## Data Preprocessing

The dataset was checked and cleaned before analysis.

The preprocessing included:

- Checking missing values
- Handling missing numerical values using median imputation
- Checking and removing duplicate records
- Converting the date column into a proper datetime format
- Creating derived date features
- Standardizing inconsistent marketing channel labels
- Standardizing region values
- Detecting potential outliers using the IQR method
- Applying IQR-based capping to selected numerical variables
- Validating the cleaned dataset

After preprocessing, the cleaned dataset was used for further exploratory analysis.

## Exploratory Data Analysis

The project includes:

- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Distribution analysis
- GroupBy aggregation
- Pivot table analysis
- Correlation analysis
- Time-based analysis

Different visualizations such as histograms, bar charts, pie charts, box plots, scatter plots, line charts, and heatmaps were used to understand the data.

## Key Findings

Some of the major findings from the analysis are:

- Social Media is the most frequently used marketing channel in the dataset.
- Influencer campaigns have the highest average sales revenue among the analyzed channels.
- Average sales revenue varies across different regions.
- The West region shows the highest average sales revenue, while the South region shows the lowest.
- Click-through rate has a weak positive relationship with sales revenue.
- Market reach has a weak positive relationship with sales revenue.
- Advertising spend has only a very weak positive linear relationship with sales revenue.
- Sales revenue varies across marketing channels and customer segments.
- Monthly average sales revenue shows variation over time.
- Several marketing and business variables show relationships with sales revenue, but no single numerical variable demonstrates a strong linear relationship with revenue.

## Business Recommendations

Based on the analysis, the project recommends:

- Monitoring marketing channel performance regularly
- Comparing campaign performance across customer segments
- Considering regional differences when planning campaigns
- Evaluating engagement metrics such as click-through rate alongside advertising spend
- Using customer and campaign characteristics to support targeted marketing strategies
- Monitoring revenue trends over time to identify changing campaign performance
- Further analyzing multiple factors together rather than relying on a single marketing metric

This project demonstrates an end-to-end Data Analytics workflow, from data understanding and preprocessing to exploratory data analysis, visualization, insight generation, and business recommendations.
