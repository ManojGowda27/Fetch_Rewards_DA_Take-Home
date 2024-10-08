# Exploratory Data Analysis (EDA)

This take-home test consists of three Jupyter notebooks where exploratory data analysis (EDA) is performed on user, transaction, and product datasets. The goal is to provide insights into the data through cleaning, transformation, and visualization steps.

## 1. **User EDA**

**Notebook:** `user_Takehome_EDA.ipynb`

### Overview
In this notebook, we focus on analyzing the users dataset, which includes demographic information such as birth dates, genders, and account creation dates. The main steps in this notebook include:
1. Loading the user data.
2. Data cleaning and standardization.
3. Visualizing key metrics to understand the user demographics.

### Key Highlights
- **Datetime Conversion:** Converted `CREATED_DATE` and `BIRTH_DATE` columns to datetime format for better analysis.
- **Gender Mapping:** Mapped the gender values to ensure consistency across the dataset. Non-standardized values were fixed to a common format.
- **Language Standardization:** Standardized regional language codes to simplify analysis (e.g., `es-419` to `es`).

### Visualizations
1. **Age Distribution of Users:** Shows the age demographics of the user base, highlighting the age range most common among users.
2. **Language Preferences:** Visualizes the distribution of languages used by users, which can be beneficial for localization efforts.
3. **Account Creation Over Time:** A time series plot to identify trends in account creation, revealing spikes in user registration.

---

## 2. **Transactions EDA**

**Notebook:** `transactions_Takehome_EDA.ipynb`

### Overview
This notebook handles the transactions data, aiming to provide insights into purchasing behavior and transactional trends. Key tasks include data cleaning, missing value treatment, and generating meaningful visualizations.

### Key Highlights
- **Data Overview and Cleaning:** Reviewed the dataset structure, identified missing values, and addressed them to ensure accuracy in analysis.
- **Datetime Operations:** Performed operations to extract transaction dates and calculate transaction frequencies.

### Visualizations
1. **Transaction Distribution by State:** A geographical breakdown showing where most transactions occur.
2. **Gender-based Transaction Distribution:** Highlighted the distribution of transactions based on user gender, offering insights into potential gender-based purchasing patterns.

---

## 3. **Products EDA**

**Notebook:** `products_Takehome_EDA.ipynb`

### Overview
The products notebook focuses on analyzing the available products in the dataset. Key analyses include the distribution of products across different categories, brands, and manufacturers.

### Key Highlights
- **Category Analysis:** The notebook examines the distribution of products across various primary and secondary categories (`CATEGORY_1` and `CATEGORY_2`).
- **Brand and Manufacturer Insights:** Identified the top brands and manufacturers by the number of products offered.

### Visualizations
1. **Distribution of Products by Category:** Visualizes the distribution of products across different primary categories (`CATEGORY_1`), helping to understand the variety of products.
2. **Top 10 Brands by Product Count:** Shows the brands that offer the most products, potentially identifying key players in the market.
3. **Top 10 Manufacturers:** Highlights the manufacturers with the most product listings.

---

## Conclusion
This is exploratory data analysis on user, transaction, and product datasets. Each notebook includes critical steps such as data cleaning, transformation, and visualization, helping to extract meaningful insights that can inform business decisions. By visualizing trends and patterns, we can understand user demographics, transaction behaviors, and product variety.

