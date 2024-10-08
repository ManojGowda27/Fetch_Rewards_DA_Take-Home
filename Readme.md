# Take-Home Test Submission

This repository contains four key Jupyter notebooks focused on Exploratory Data Analysis (EDA) and SQL queries. The objective of this is to answer business-related questions through data analysis, using both SQL and Python to manipulate and visualize data. Below is a detailed description of each notebook.

## Table of Contents
1. [Files Overview](#files-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Conclusion](#conclusion)

## Files Overview

### 1. `user_Takehome_EDA.ipynb`[Code_Preview](#EDA/user_Takehome_EDA.ipynb)
This notebook focuses on analyzing the users dataset, which includes demographic details such as birth dates, gender, and account creation dates. The key objectives of this notebook are:
- **Data Cleaning:** Converting columns like `CREATED_DATE` and `BIRTH_DATE` to a proper datetime format.
- **Standardization:** Gender values and language codes are mapped to a standardized format to ensure consistency.
- **Visualizations:**
  - **Age Distribution of Users:** Displays the distribution of users based on their age.
  - **Language Preferences:** Shows the preferred languages used by the user base.
  - **Account Creation Trends:** A time series plot showing account creation trends over time.
  
This notebook provides insights into the user demographics and their behaviors within the platform.

### 2. `transactions_Takehome_EDA.ipynb`[Code_Preview](#EDA/transactions_Takehome_EDA.ipynb)
The second notebook deals with the transactions data and focuses on analyzing purchasing patterns and transactional behaviors. Key steps include:
- **Data Overview and Cleaning:** Summary of missing values and handling outliers.
- **Data Transformations:** Formatting transaction dates and merging them with user data.
- **Visualizations:**
  - **Transaction Distribution by State:** A geographical breakdown of where transactions occur.
  - **Gender-based Transaction Analysis:** Distribution of transactions based on user gender.
  
The goal of this notebook is to provide insights into where transactions are happening and if any demographic-based patterns exist.

### 3. `products_Takehome_EDA.ipynb`[Code_Preview](#EDA/products_Takehome_EDA.ipynb)
This notebook analyzes the product dataset, focusing on the distribution of products across categories, brands, and manufacturers. Key analyses include:
- **Category Distribution:** The distribution of products across different primary and secondary categories.
- **Brand and Manufacturer Insights:**
  - **Top 10 Brands by Product Count:** Identifying the most prevalent brands.
  - **Top 10 Manufacturers:** Highlighting manufacturers with the highest number of products.

The notebook provides a deep dive into product diversity and key players in terms of product offerings.

### 4. `queries.ipynb`
This notebook contains SQL queries and Python code that answers specific business-related questions. Key queries include:
- **Top 5 Brands by Receipts Scanned for Users 21 and Over:** A query that identifies the top-performing brands based on the number of receipts scanned.
- **Percentage of Sales in Health & Wellness Category by Generation:** A query that calculates the percentage of sales for the Health & Wellness category, segmented by user generations (Gen Z, Millennials, Gen X, and Boomers).
- **Python Code for Power Users Analysis:** Python code that identifies high-spending users who have more than 100 receipts, sorted by total sales.

This notebook demonstrates the use of SQL for answering data-related business questions, and Python for further data manipulations and insights.

## Installation
To run these notebooks on your local machine, you will need to install the following dependencies:

1. Python 3.x
2. Jupyter Notebook or JupyterLab
3. Required Python Libraries:
   - Pandas
   - Matplotlib
   - Seaborn

You can install these packages via `pip`:
```bash
pip install pandas matplotlib seaborn
