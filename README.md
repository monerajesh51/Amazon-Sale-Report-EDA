# Amazon-Sale-Report-EDA
Project Overview

This project performs Exploratory Data Analysis (EDA) on an Amazon sales dataset to understand sales patterns, product performance, and customer ordering trends.
The dataset contains 128,975 records and 24 columns, including order details, product categories, shipping locations, and sales amounts.

The objective of this analysis is to clean the dataset, explore important variables, and extract meaningful business insights using data visualization and statistical techniques.

🎯 Objectives

Understand the structure and distribution of the dataset

Perform data cleaning and preprocessing

Detect and remove duplicate records and missing values

Identify outliers in sales amount

Analyze product categories, shipping locations, and fulfillment methods

Visualize sales trends over time

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib
In this project, I performed Exploratory Data Analysis (EDA) on an Amazon sales dataset containing 128,975 records and 24 columns to understand sales patterns and business insights.

🔹 Steps Performed

1️⃣ Data Loading & Exploration

Loaded the dataset using Pandas.

Examined dataset structure using shape, head, tail, and info to understand columns and data types.

2️⃣ Data Cleaning

Removed unnecessary columns (index, Unnamed: 22).

Checked and removed duplicate records based on Order ID, SKU, and Date.

Identified and handled missing values by removing rows with null values.

3️⃣ Outlier Detection

Used boxplots and IQR method to detect and remove outliers in the Amount column.

4️⃣ Exploratory Data Analysis

Generated descriptive statistics for numerical and categorical variables.

Analyzed unique values across columns to understand product and location diversity.

5️⃣ Data Visualization

Created visualizations using Matplotlib and Seaborn:

Correlation heatmap for numerical relationships

Top product categories

Sales trends over time

Top shipping cities

Fulfillment distribution

6️⃣ Key Insights

Most sales came from Set and Kurta categories.

Bengaluru, Hyderabad, and Mumbai were the top ordering cities.

Majority of orders were fulfilled by Amazon.

Sales showed seasonal peaks during April–May.

Seaborn

Google Colab / Jupyter Notebook
