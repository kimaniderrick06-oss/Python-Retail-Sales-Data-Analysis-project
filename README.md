# Python-Retail-Sales-Data-Analysis-project
I cleaned a messy retail sales dataset ,analyzed and created visualizations using matplotlib, seaborn , numpy and pandas on jupyter notebook.

## Project Title

**Retail Sales Data Cleaning, Exploratory Data Analysis (EDA), and Business Insights using Python**

---

# Executive Summary

This project analyzes a retail sales dataset containing customer, product, transaction, and financial information. The dataset was intentionally messy and required extensive data cleaning before meaningful analysis could be performed.

Using **Python (Pandas, NumPy, Matplotlib, and Seaborn)**, I cleaned the data, performed exploratory data analysis (EDA), engineered new features, and answered key business questions related to sales performance, profitability, customer behavior, and pricing strategies.

The final output provides actionable insights that can help management improve decision-making regarding product performance, customer segmentation, pricing, discount strategies, and regional sales.

---

# Business Objective

The objective of this project was to transform raw transactional data into meaningful business insights by:

* Cleaning inconsistent and incomplete data
* Preparing the dataset for analysis
* Identifying sales and profit drivers
* Understanding customer purchasing behavior
* Evaluating pricing and discount strategies
* Creating visualizations that communicate business performance effectively

---

# Dataset Overview

The dataset contains information on:

* Customer demographics
* Products purchased
* Transaction details
* Sales revenue
* Product costs
* Discounts
* Profits
* Payment methods
* Geographic information

The original dataset contained numerous quality issues that prevented reliable analysis.

---

# Data Quality Assessment

A comprehensive data quality assessment identified several issues:

### Missing Values

* Missing customer ages
* Missing payment methods
* Missing shipping methods
* Missing profits
* Missing promo codes
* Missing product categories

### Inconsistent Categories

Examples included:

* Gender:

  * M
  * m
  * FEMALE
  * Unknown

* Payment Method:

  * CC
  * Cash
  * CASH
  * paypal

* Returned Item:

  * Yes
  * Y
  * True
  * No
  * False

### Invalid Data Formats

Examples included:

* Age:

  * "thirty"
  * "18-25"
  * "40+"

* Quantity:

  * "two"
  * "three"

* Unit Price:

  * "price"

### Outliers

Potential outliers included:

* Ages above 100
* Negative quantities
* Invalid ZIP codes
* Negative profits

---

# Data Cleaning Process

The following steps were performed:

* Removed unnecessary columns
* Standardized categorical variables
* Converted dates to datetime format
* Converted numeric columns to appropriate data types
* Treated missing values
* Corrected inconsistent labels
* Created new analytical features

New columns created:

* Month
* Month Number
* Year
* Year-Month
* Age Group
* Gross Sales
* Discount Amount
* Profit Margin

---

# Exploratory Data Analysis

The cleaned dataset was analyzed to answer key business questions.

## 1. Which product categories generate the highest revenue and profit?

Purpose:
Identify the company's strongest performing product categories.

Business Value:
Supports inventory planning and marketing investment.

Visualization:
Horizontal Bar Chart

---

## 2. How do discounts affect revenue and profit?

Purpose:
Evaluate whether discount strategies improve or reduce profitability.

Business Value:
Supports pricing strategy decisions.

Visualization:
Scatter Plot

---

## 3. Which customer age groups generate the highest revenue?

Purpose:
Identify the company's most valuable customer segments.

Business Value:
Improves customer targeting and marketing campaigns.

Visualization:
Bar Chart

---

## 4. Which regions generate the highest sales?

Purpose:
Compare revenue and profit across cities and states.

Business Value:
Supports expansion and regional marketing strategies.

Visualization:
Bar Chart and Geographic Map

---

## 5. Which products are the most profitable?

Purpose:
Identify products contributing the highest profit.

Business Value:
Supports product portfolio optimization.

Visualization:
Top 10 Horizontal Bar Chart

---

## 6. Is there a relationship between product price and purchase quantity?

Purpose:
Determine whether pricing influences purchasing behavior.

Business Value:
Supports pricing optimization.

Visualization:
Scatter Plot

---

## 7. Which payment methods are associated with higher-value purchases?

Purpose:
Compare customer spending across payment methods.

Business Value:
Improves understanding of customer purchasing behavior.

Visualization:
Box Plot

---

## 8. How do sales and profits change over time?

Purpose:
Monitor business performance over multiple months.

Business Value:
Supports forecasting and seasonal planning.

Visualization:
Line Chart

---

## 9. Which financial variables influence profitability?

Purpose:
Study the relationships between:

* Unit Price
* Discount
* Cost
* Revenue
* Profit

Business Value:
Helps management understand profit drivers.

Visualization:
Correlation Heatmap

---

## 10. Which customer segments generate the highest Average Order Value?

Purpose:
Identify customers with the highest purchasing power.

Business Value:
Supports loyalty programs and customer retention strategies.

Visualization:
Grouped Bar Chart

---

# Key Performance Indicators (KPIs)

The following KPIs were created:

* Total Revenue
* Total Profit
* Total Orders
* Total Customers
* Average Order Value (AOV)
* Profit Margin
* Average Discount
* Revenue per Customer

These KPIs provide a high-level overview of overall business performance.

---

# Tools and Technologies

Programming Language:

* Python

Libraries:

* Pandas
* NumPy
* Matplotlib
* Seaborn

Business Intelligence:

* Power BI

Development Environment:

* Jupyter Notebook

Version Control:

* GitHub

---

# Key Skills Demonstrated

This project demonstrates proficiency in:

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Business Analytics
* Data Visualization
* Dashboard Design
* Statistical Analysis
* Python Programming
* Power BI Reporting

---

# Business Recommendations

Based on the analysis, management should consider:

* Increasing investment in high-profit product categories.
* Reviewing discount strategies that reduce profitability.
* Targeting high-value customer segments with personalized promotions.
* Expanding marketing efforts in high-performing geographic regions.
* Reviewing pricing strategies for low-profit products.
* Monitoring monthly sales trends to improve forecasting and inventory planning.

---

# Conclusion

This project demonstrates the complete data analysis workflow, from transforming raw, messy data into a clean analytical dataset to generating business insights through visualization and reporting.

The combination of Python for data preparation and analysis and Power BI for interactive dashboards showcases the practical skills required of a Data Analyst.

The project emphasizes not only technical proficiency but also the ability to translate data into actionable business recommendations that support informed decision-making.

