**SWYNEX Final Data Analytics Project**

**Online Retail — End-to-End Sales & Customer Analytics**

**1. Project Overview**

This project was completed as part of the SWYNEX Technologies Data Analyst Internship. It brings together data cleaning, exploratory data analysis (EDA), business insights, and interactive dashboard development using the Online Retail dataset.

The objective is to transform raw retail transaction data into meaningful insights that can support business decision-making.

**2. Business Problem**

Retail businesses need to understand sales performance, customer activity, product demand, and revenue trends to make informed decisions.

This project explores the following questions:

- How much revenue and sales volume did the business generate?
- How does revenue change over time?
- Which countries contribute the most revenue?
- Which products perform best by revenue and quantity?
- How can interactive reporting help users explore sales performance?

**3. Dataset Information**

Dataset: UCI Online Retail dataset
Domain: Retail and E-commerce Analytics

The dataset contains transaction-level information, including invoice numbers, product codes, descriptions, quantities, invoice dates, unit prices, customer IDs, and countries.

The cleaned dataset contains 524,878 records and 9 columns.

**4. Data Cleaning and Preparation**

Data preparation was performed using Power Query.

Key steps included:

- Removed duplicate records.
- Excluded transactions with non-positive quantities.
- Excluded transactions with non-positive unit prices.
- Standardized data types.
- Replaced missing Customer IDs with "0" to identify records with unknown customers.
- Trimmed and standardized product descriptions.
- Created a Total Amount column using Quantity × Unit Price.

The cleaned dataset was used for subsequent analysis and dashboard development.

**5. Exploratory Data Analysis**

Exploratory data analysis was performed using Python in Google Colab.

The analysis included:

- Descriptive statistics for quantity, unit price, and transaction amount.
- Revenue and quantity summaries.
- Monthly revenue trends.
- Revenue contribution by country.
- Product performance by revenue and quantity.
- Identification of unusual high-volume transactions for further validation.

**6. Power BI Dashboard**

An interactive dashboard was developed in Microsoft Power BI to present the main findings.

**Key Performance Indicators**

- Total Revenue: approximately £10.64 million
- Total Quantity: 5,572,420
- Total Invoices: 19,960
- Average Order Value: approximately £533.17
- Total Customers: 4,338

**Visualizations**

- Monthly Revenue Trend
- Revenue by Country
- Top 10 Products by Revenue
- Top 10 Products by Quantity

**Interactive Filters**

- Country
- Invoice Date
- Customer ID

**7. Key Business Insights**

- Total revenue in the cleaned dataset is approximately £10.64 million.
- The United Kingdom contributes approximately 84.59% of total revenue.
- November 2011 recorded the highest monthly revenue in the analyzed data.
- The top 10 product descriptions by revenue contribute approximately 10.84% of total revenue.
- Approximately 25.18% of cleaned records have an unidentified Customer ID. This limits customer-level analysis for those transactions.
- An unusually high-volume transaction was identified for further validation rather than automatically treated as an error.

**8. Business Recommendations**

- Investigate the strong revenue concentration in the United Kingdom and evaluate opportunities in other markets.
- Review monthly sales patterns to support seasonal inventory and sales planning.
- Monitor high-revenue products and high-volume products separately because revenue and quantity measure different aspects of performance.
- Improve customer identification at checkout to strengthen customer segmentation and retention analysis.
- Validate unusual high-volume transactions before using them for forecasting or operational decisions.

**9. Tools and Technologies**

- Microsoft Excel
- Power Query
- Python
- Pandas
- NumPy
- Matplotlib
- Microsoft Power BI
- DAX
- GitHub

**10. Project Workflow**

1. Data cleaning and preparation
2. Exploratory data analysis
3. Business insight generation
4. Interactive dashboard development
5. Documentation and portfolio presentation

**11. Project Deliverables**

This repository documents the end-to-end case study and includes the relevant project files, analysis, and dashboard materials.

**12. Conclusion**

This project demonstrates an end-to-end retail analytics workflow, from data preparation to exploratory analysis and interactive business reporting. It helped strengthen practical skills in data cleaning, Python-based analysis, Power BI, data visualization, and communicating business insights.

**Program:** SWYNEX Technologies — Data Analyst Internship
**Final Task:** Task 4 — Final Data Analytics Project
