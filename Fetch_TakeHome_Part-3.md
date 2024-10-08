#### **Construct an email or slack message that is understandable to a product or business leader who is not familiar with your day-to-day work. Summarize the results of your investigation.**

### **Subject: Summary of Key Insights and Data Quality Issues from EDA**

Hi \[Product Leader's Name\],

I wanted to share a summary of the exploratory data analysis (EDA) I performed on the datasets from the recent project. Below are the key findings, interesting trends, and some areas where further clarification or action is needed to ensure data accuracy.

### **1\. Key Data Quality Issues:**

* **Inconsistent Gender Data:** In the `USER_TAKEHOME` dataset, the `GENDER` column contains several variations of similar categories (e.g., "Prefer not to say" and "prefer not to say"). These inconsistencies were mapped to more standardized categories (e.g., `prefer_not_to_say`, `non-binary`, and `unspecified`), but I would recommend a review of how this data is being captured to avoid these discrepancies in the future.  
* **Timezone Awareness Issues in `CREATED_DATE`:** Some date fields, such as `CREATED_DATE`, are timezone-aware while others are timezone-naive. This led to issues during analysis when calculating user account age, and I've made sure to standardize the dates, but a clearer understanding of the data's time zone handling would be helpful.  
* **Missing Sales Data:** There are several `FINAL_SALE` values that are either missing or incorrectly formatted, which may skew analysis around total sales and brand performance.

### **2\. Interesting Trend:**

* **Top Performing Brands for Long-Term Users:** Analyzing users with accounts older than 6 months revealed that the **top 5 brands by total sales** are primarily from the `Health & Wellness` category. This indicates that users who stay longer tend to gravitate toward health-focused products. This trend can be valuable for tailoring marketing efforts or product recommendations to long-term users.

### **3\. New Insight:**

* **Power Users Contribution:** Upon reviewing the transactions, I discovered that **power users**—those who have scanned over 100 receipts—contribute disproportionately to overall sales. These users not only account for a large number of receipts but also tend to spend more on higher-priced brands, especially in the `Health & Wellness` and `Snacks` categories. Identifying and nurturing these power users could lead to increased brand loyalty and revenue.

### **Request for Action:**

To improve the quality and depth of future analyses, I recommend the following:

* **Clarify Timezone Handling:** Can we confirm how timezone data is being managed across the system? This would help avoid future discrepancies when calculating date-related metrics.  
* **Review Sales Data Quality:** It would be helpful to investigate why some `FINAL_SALE` values are missing or incorrectly formatted and whether there are any data collection issues at the transaction level.  
* **Gender Data Consistency:** Streamlining how gender data is captured would make it easier to analyze user demographics accurately. Are there any efforts underway to standardize these input fields?

Please let me know if you need any further details or if there’s a specific direction you’d like to explore next.

Best,

Manoj

