## Project Overview: SaaS Sales Data Analysis (Capstone Module 2)

This project analyzes **sales and profit data** from a Software-as-a-Service (SaaS) company to understand which products, regions, and customers contribute most to the company’s profits.  
The goal is to help the business make **data-driven decisions** to improve performance, control discounts, and focus on high-profit products.

The dataset comes from AWS SaaS sales data on Kaggle, which includes information such as **sales amount, profit, discount, customer name, product category, and region**.

### Objectives
- Find the main factors that affect sales and profit.  
- Identify which products and regions bring in the most profit.  
- Suggest strategies to increase overall profitability.
  
### Methods Used
1. **Data Cleaning** – fixed missing values, corrected data types, removed duplicates, and handled outliers using the IQR method.  
2. **Exploratory Data Analysis (EDA)** – explored data using charts and summary tables to find sales and profit patterns.  
3. **Statistical Testing** – used correlation and normality tests to check relationships between sales, profit, and time.  
4. **Feature Engineering** – added new columns such as `order_year` and `order_month` to analyze time-based trends.  
5. **Visualization** – created clear graphs and charts to explain findings.  

### Key Insights
- **Sales are not always equal to profit** — some products sell well but have small profit margins.  
- **No clear growth trend over time**, meaning sales and profit do not depend on specific months or seasons.  
- The **West region** performs better than other regions due to balanced discount and cost management.  
- **Too much discounting** lowers profit significantly.  

### Recommendations
- Focus marketing on **high-margin products** instead of just high sales.  
- Reevaluate **discount policies** to prevent profit loss.  
- Learn from the **West region’s** successful pricing and cost strategies.  
- Promote products with **steady sales and good profit margins**.  

### Tools and Libraries
- **Python 3**  
- **pandas**, **NumPy**, **matplotlib**, **seaborn**, **SciPy**  
- **Jupyter Notebook / Google Colab** for analysis  
- **Tableau** for data visualization dashboards  
