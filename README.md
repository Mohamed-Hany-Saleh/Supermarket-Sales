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
### Data Overview
> ![Data Gathering](https://github.com/user-attachments/assets/3249fff7-4294-426e-aea7-ccaf51590dcd)

### Data Cleaning
![Fixing Tidiness issues](https://github.com/user-attachments/assets/f12d4bbe-f71d-4f58-bdd4-f742f638f183)


![Test](https://github.com/user-attachments/assets/2d74f281-4138-4706-a6f0-d75a68bfb103)


![Fixing Quality Issues](https://github.com/user-attachments/assets/067c8baf-8d3a-41e4-bddb-f1d2853084b3)


![Change column names](https://github.com/user-attachments/assets/52361336-8664-4e99-b4f7-52ba7499ef90)


### Cleaned Data Overview
![Data Assessing After Cleaning](https://github.com/user-attachments/assets/c4a6c34a-adf7-4561-8c41-6b60bea432c9)

### 4. Storing
The cleaned data was stored in a CSV file using Pandas, ready for further analysis in Power BI.

---

## Dashboards
This section includes key dashboards that provide insights into supermarket sales. The dashboards cover various KPIs, including total sales, profit margins, and customer behavior analysis.

1. **Overview**  
   > ![Overview](https://github.com/user-attachments/assets/122f8cc4-38a0-40cb-97dd-e7aaaa48638d)
  
   

2. **Sales and Customer**  
   > ![Sales and Customer](https://github.com/user-attachments/assets/8b11bf83-36cf-4a8d-8dde-121038a9f057)
   
   
3. **Product Line Performance** 
   > ![Product Line Performance](https://github.com/user-attachments/assets/5394477d-65a4-49a6-a193-2de2dc7dd7c2)
  
   

4. **Sales and Transaction Insights**  
   > ![Sales and Transaction Insights](https://github.com/user-attachments/assets/606006a6-2188-4df7-b60a-a4d0be3393db)
   
  

5. **Rating and Sales Analysis**  
   > ![Rating and Sales Analysis](https://github.com/user-attachments/assets/1b4cd32b-2f3c-48dd-9b6d-5f741b69f6db)
  
  

6. **Profit Analysis**  
   > ![Profit Analysis](https://github.com/user-attachments/assets/6b823f83-912a-424b-ab28-68b99ce4245d)
  

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

![Screenshot 2024-09-13 161518](https://github.com/user-attachments/assets/f7ec3691-3bf0-4391-bd06-b1b4e010e88d)




---

## How to Run
1. Clone this repository.
2. Install dependencies.
3. Load the cleaned dataset into Power BI for visualization.
4. View the dashboards for insights into supermarket performance.

---

## Conclusion
This project provides a holistic view of supermarket performance, with actionable insights derived from sales data, customer behavior, and profitability trends. The dashboards and analysis are essential for improving business strategies and enhancing customer satisfaction.
