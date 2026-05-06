# Customer_Behavior_Analysis
Data analytics project showcasing customer behavior analysis using python, sql , power Bi
# Customer Behavior Analysis Project

## Overview
This project focuses on analyzing customer purchasing behavior using Python, SQL, and Power BI. The goal is to extract meaningful insights from raw data, understand customer trends, and present them through an interactive dashboard.

The project covers the complete data analytics workflow: data loading, cleaning, exploration, querying, visualization, and reporting.

## Dataset

The dataset contains customer transaction and behavior details, including:

* Customer demographics (age group, gender)
* Purchase amount
* Product categories (Clothing, Accessories, Footwear, Outerwear)
* Subscription status
* Shipping type
* Review ratings

---

## Tools & Technologies

* **Python** – Data cleaning and EDA
* **Pandas, NumPy, Matplotlib, Seaborn** – Data manipulation & visualization
* **MySQL** – Querying and data analysis
* **Power BI** – Dashboard creation
* **Gamma** – Presentation (PPT)
* **Jupyter Notebook** – Development environment

## Project Workflow

### 1. Data Loading

* Loaded raw dataset into Jupyter Notebook using Pandas
* Inspected structure, columns, and data types

### 2. Data Cleaning

* Handled missing values
* Removed duplicates
* Standardized column names
* Corrected data types

### 3. Exploratory Data Analysis (EDA)

* Analyzed customer distribution
* Identified top-performing categories
* Studied purchase trends across age groups
* Visualized patterns using charts

### 4. SQL Analysis (MySQL)

* Imported cleaned dataset into MySQL
* Performed queries such as:

  * Revenue by category
  * Customers by subscription status
  * Sales by age group
  * Gender-based revenue comparison

### 5. Dashboard Creation (Power BI)

Built an interactive dashboard with:

* KPI Cards:

  * Total Customers (3.9K)
  * Average Purchase Amount ($59.76)
  * Average Rating (3.75)
* Charts:

  * Revenue by Category
  * Sales by Category
  * Revenue by Age Group
  * Sales by Age Group
  * Subscription Distribution
* Filters:

  * Gender
  * Category
  * Shipping Type
  * Subscription Status

---

## Dashboard Insights

* **Clothing** generates the highest revenue and sales
* Majority of customers are **non-subscribers (~73%)**
* **Young adults** contribute the most to revenue
* **Accessories** is the second best-performing category
* Ratings are moderate (~3.75), indicating scope for improvement

---

## Results & Key Findings

* Revenue is highly concentrated in a few categories
* Subscription conversion is low → opportunity for business growth
* Younger customers are the most valuable segment
* Product strategy should focus on high-performing categories

---

## How to Run

### 1. Python (EDA)

* Open the `.ipynb` file in Jupyter Notebook
* Install required libraries:

  ```
  pip install pandas numpy matplotlib seaborn
  ```
* Run all cells

### 2. MySQL

* Create a database
* Import dataset into a table
* Run SQL queries from the `.sql` file

### 3. Power BI

* Open `.pbix` file
* Load dataset
* Explore dashboard and filters

---

## Project Structure

```
├── data/
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
├── sql/
│   └── customer_behavior_analysis_mysql.sql
├── dashboard/
│   └── powerbi_dashboard.pbix
├── presentation/
│   └── gamma_presentation.ppt
└── README.md
```

---

## Conclusion

This project demonstrates end-to-end data analytics skills:

* Data cleaning and preprocessing
* SQL-based analysis
* Data visualization
* Dashboard building
* Business insight generation

It reflects practical, job-ready skills required for a Data Analyst role.
