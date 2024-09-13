# Supermarket Sales Data Analysis

This project provides a comprehensive analysis of supermarket sales data, focusing on key insights and business intelligence derived from sales across different branches, product lines, customer types, and more. The project includes data wrangling, dashboards created in Power BI, and an in-depth Business Insights Report.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Wrangling](#data-wrangling)
   - Gathering
   - Assessing
   - Cleaning
   - Storing
3. [Dashboards](#dashboards)
   - Key Dashboards
4. [Business Insights Report](#business-insights-report)
5. [How to Run](#how-to-run)
6. [Conclusion](#conclusion)

---

## Introduction
This project focuses on analyzing supermarket sales to derive meaningful insights that can drive decision-making and improve business performance. Using Power BI for visualizations and Python for data cleaning, we address key questions about sales performance, customer segmentation, and product profitability.

---

## Data Wrangling
### 1. Data Gathering
The dataset contains 16 columns and 1006 rows, with information like:
- Invoice number
- Branch
- Customer type
- Product type
- Quantity sold
- Price per unit
- Taxes and totals
- Payment method
- Customer ratings

### 2. Data Assessing
Initial assessment was conducted to identify issues in data quality, completeness, and accuracy. Some key findings include:
- Inconsistent pricing formats (e.g., "USD")
- Empty values in the "Total" column
- Incorrect time formats (e.g., "(pm)" indicators)

### 3. Data Cleaning
Steps taken to clean the dataset:
- Removed currency symbols (e.g., "USD")
- Corrected the time formats
- Filled missing values for totals and taxes
- Removed duplicates and handled negative/invalid entries
- Ensured proper data types for date and price columns

> **Image Placeholder: Data Cleaning Code from Wrangling Sales.ipynb**  
> _This is where the image of the data cleaning process in Colab will be placed._

### 4. Storing
The cleaned data was stored in a CSV file using Pandas, ready for further analysis in Power BI.

---

## Dashboards
This section includes key dashboards that provide insights into supermarket sales. The dashboards cover various KPIs, including total sales, profit margins, and customer behavior analysis.

1. **Total Sales by Product Line and Branch**  
   > **Image Placeholder: Total Sales by Product Line and Branch**  
   _An overview of sales performance across different product lines and branches._

2. **Customer Segmentation by Purchase Frequency**  
   > **Image Placeholder: Customer Segmentation by Purchase Frequency**  
   _A visual analysis of customer types and their purchasing behavior._

3. **Gender-Based Product Preferences**  
   > **Image Placeholder: Gender-Based Product Preferences**  
   _Insights into which products are favored by male versus female customers._

4. **Sales and Profit Margin Analysis**  
   > **Image Placeholder: Sales and Profit Margin Analysis**  
   _A comparison of sales figures against profit margins across branches and product lines._

5. **Sales Performance over Time (Daily)**  
   > **Image Placeholder: Sales Performance over Time (Daily)**  
   _Tracking daily sales performance to identify trends and peaks in sales._

6. **Customer Satisfaction by Branch and Product Line**  
   > **Image Placeholder: Customer Satisfaction by Branch and Product Line**  
   _Customer feedback and ratings visualized against branch and product line performance._

---

## Business Insights Report
### Executive Summary of Supermarket Sales Performance Report
The report dives deep into the sales performance across multiple dimensions—branches, product lines, and customer segments—highlighting key takeaways and trends.

#### 1. Total Sales
The total revenue from all sales transactions across product lines, customer types, and branches was analyzed:
- **Product Line Breakdown:** Food and Beverages lead in total sales with $56k, followed by Sports and Travel at $55k.
- **Customer Type Breakdown:** Normal customers generated more revenue than Member customers.
- **Branch Breakdown:** Branch C had the highest sales, while Branches A and B were closely behind.

#### 2. Gender-Based Insights
Male and female customers exhibited distinct preferences in certain product categories, with females showing higher spending in Fashion and Lifestyle, while males dominated in Health and Beauty.

#### 3. Profit and Unit Price Analysis
The Fashion and Sports categories had the highest average unit prices, but Food and Beverages led in total profit.

#### 4. Customer Satisfaction and Sales
A strong correlation was identified between high customer satisfaction (rating) and high sales in both product lines and branches, with Branch C and the Food and Beverages category standing out.

> **Image Placeholder: Sales and Customer Satisfaction Analysis Chart**  
> _This chart shows the relationship between sales and customer satisfaction._

---

## How to Run
1. Clone this repository.
2. Install dependencies.
3. Load the cleaned dataset into Power BI for visualization.
4. View the dashboards for insights into supermarket performance.

---

## Conclusion
This project provides a holistic view of supermarket performance, with actionable insights derived from sales data, customer behavior, and profitability trends. The dashboards and analysis are essential for improving business strategies and enhancing customer satisfaction.
