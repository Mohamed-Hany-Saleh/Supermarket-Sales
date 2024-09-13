# Supermarket Sales Data Analysis

## Project Overview
This project focuses on cleaning, analyzing, and visualizing supermarket sales data to uncover key business insights. The analysis is performed in three key phases:
1. **Data Wrangling**: Cleaning the raw sales data to make it ready for analysis using Python.
2. **Dashboard Creation**: Visualizing key metrics and insights using Power BI.
3. **Business Insights Report**: Summarizing the findings and providing actionable insights for decision-making.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Description](#dataset-description)
3. [Data Wrangling Process](#data-wrangling-process)
   - Data Gathering
   - Data Assessing
   - Data Cleaning
4. [Data Analysis and Visualizations](#data-analysis-and-visualizations)
5. [Business Insights](#business-insights)
6. [How to Run](#how-to-run)
7. [Future Work](#future-work)

---

## Introduction
The **Supermarket Sales Data Analysis** project explores sales transactions from multiple branches to extract valuable insights related to customer preferences, product performance, and payment methods. The dataset was cleaned using Python in **Google Colab** (**Wrangling Sales.ipynb**) and visualized using **Power BI**.

---

## Dataset Description
The dataset consists of 1006 rows and 16 columns, capturing sales transactions including:
- **Invoice Number**
- **Branch**
- **Customer Type**
- **Product Line**
- **Quantity Sold**
- **Price per Unit**
- **Taxes**
- **Total**
- **Payment Method**
- **Customer Ratings**

---

## Data Wrangling Process
### 1. Data Gathering
The data was initially collected from the supermarket's sales system. It contained information about sales, customer preferences, and payment methods.

### 2. Data Assessing
Before cleaning, the dataset was assessed for the following issues:
- **Quality Issues**: Inconsistent formats, missing data, and erroneous values.
- **Completeness**: Missing values in critical columns such as total amounts and taxes.

_**[Insert Image 1: Initial Dataset Overview from Wrangling Sales.ipynb]**_

### 3. Data Cleaning
The cleaning process addressed the following:
- Removed "USD" from the **Unit Price** column.
- Filled missing values for **Total** by calculating: `Quantity * Unit Price + 5% Tax`.
- Fixed formatting issues in the **Time** and **Date** columns.
- Renamed columns for clarity (e.g., **Invoice_ID**, **Product_Line**, **Tax_5%**).
- Replaced negative and incorrect values.

_**[Insert Image 2: Cleaning Steps in Wrangling Sales.ipynb]**_

After cleaning, the data was reassessed to ensure there were no missing values or inconsistencies.

_**[Insert Image 3: Cleaned Data Overview from Wrangling Sales.ipynb]**_

### 4. Data Storing
The cleaned data was stored in a **CSV** file and is ready for analysis and visualization.

---

## Data Analysis and Visualizations
The next step is creating insightful visualizations using **Power BI**. Key visualizations include:
- **Sales Trends by Branch**
- **Customer Preferences by Product Line**
- **Impact of Discounts on Sales**
- **Sales Distribution by Payment Method**

_**[Placeholder for Power BI Dashboard Screenshot]**_

---

## Business Insights
Based on the data analysis, key insights were extracted that can help the supermarket management make better business decisions. These insights will be compiled into a detailed **Business Insights Report**, which includes:
- The performance of different branches.
- Popular products among different customer types.
- Payment preferences and their impact on sales.

---

## How to Run
To run the data wrangling process, you can follow these steps:
1. Open the **Wrangling Sales.ipynb** file in **Google Colab**.
2. Run each cell to clean and process the dataset.
3. Export the cleaned data as a **CSV** file.
4. Open **Power BI Desktop** and import the cleaned data for visualization.

---

## Future Work
The project will continue with the following updates:
- Adding more advanced visualizations in **Power BI**.
- Finalizing the **Business Insights Report**.
- Exploring additional predictive models based on sales trends.

Stay tuned for more updates!

