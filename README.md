# food-delivery-eda-bangalore
Exploratory Data Analysis of online food delivery preferences in Bangalore using Python. The project analyzes customer demographics, ordering behavior, and service issues to extract actionable business insights using Pandas, Matplotlib, and Seaborn.
# Exploratory Data Analysis on Online Food Delivery Preferences (Bangalore)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a dataset representing food delivery preferences in the Bangalore region. The goal is to uncover patterns in customer behavior, identify key factors influencing ordering decisions, and highlight operational challenges affecting customer satisfaction.

## Objectives

* Understand customer demographics and behavior
* Analyze ordering patterns and preferences
* Identify key issues impacting user experience
* Generate actionable business insights

## Dataset Description

The dataset includes the following types of features:

* Demographics: Age, Gender, Marital Status, Occupation, Monthly Income
* Behavioral Data: Order Time, Meal Preferences, Ordering Medium
* Customer Feedback: Delivery issues, hygiene concerns, service quality
* Location Data: Latitude, Longitude, Pin Code

## Tools and Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## EDA Tasks Performed

### 1. Data Understanding

* Used `.info()` to inspect data types and missing values
* Used `.describe()` for statistical summaries
* Used `.value_counts()` for categorical distributions

### 2. Univariate Analysis

* Histogram for Age distribution
* Bar charts for Monthly Income and Order Time
* Count plots for categorical variables

### 3. Bivariate Analysis

* Gender vs Order Time using count plots
* Income vs ordering patterns
* Scatter plot between Age and Family Size

### 4. Multivariate Analysis

* Heatmap to identify correlations between numerical variables
* Pairplot for selected features

### 5. Customer Issue Analysis

* Analyzed responses for:

  * Late Delivery
  * Poor Hygiene
  * Missing Items
  * Wrong Orders
* Converted ordinal responses into numerical scale for deeper insights

## Key Findings

* A large proportion of users fall under the "No Income" category, indicating that students form a major user base
* Orders are most frequent during evenings and weekends, suggesting demand is driven by leisure time
* Late delivery and hygiene issues are the most common customer complaints
* Younger users (primarily between ages 20–35) dominate the platform usage

## Business Insights

* Target student segment with affordable pricing and discounts
* Improve delivery efficiency to reduce delays
* Focus on hygiene and quality to enhance customer trust
* Optimize operations during peak hours (evenings and weekends)

## Conclusion

The analysis highlights that food delivery usage is largely influenced by convenience and lifestyle factors. Addressing operational challenges and focusing on key customer segments can significantly improve customer satisfaction and business performance.

## Project Structure

* `data/` – Dataset files
* `notebooks/` – Jupyter Notebook containing EDA
* `report/` – PDF report of findings
* `README.md` – Project documentation

## How to Run

1. Clone the repository
2. Install required libraries:

   ```
   pip install pandas matplotlib seaborn
   ```
3. Open the Jupyter Notebook
4. Run all cells to reproduce the analysis

## Future Improvements

* Include predictive modeling for customer behavior
* Perform clustering for customer segmentation
* Add interactive dashboards using Power BI or Tableau
