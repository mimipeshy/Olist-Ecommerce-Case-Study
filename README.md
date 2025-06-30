# Customer Segmentation & Revenue Insights — UK Online Retail Dataset

## 🚀 Project Overview
This project analyzes customer purchasing behavior using the UK Online Retail Dataset (Kaggle/UCI). The goal is to help the business identify high-value customer segments, uncover revenue patterns, and drive retention strategies using RFM (Recency, Frequency, Monetary) Analysis.

✅ Tools Used:

- Power BI
- Excel (Power Query, Pivot Tables)

✅ Dataset:

UK Online Retail II Dataset (https://lnkd.in/eH92RFPs)

## 🎯 Business Objectives
- Segment customers based on purchasing behavior.
- Identify Champions, Loyal, At Risk, and Lost Customers.
- Understand revenue distribution across customer segments.
- Discover peak sales periods and trends.
- Recommend data-driven strategies to increase retention and revenue.

## 🗺️ Dataset Overview
| Column  | Description|
| ------------- | ------------- |
| InvoiceNo	    |Unique transaction ID|
| StockCode	    |Product ID|
| Description	|Product name|
| Quantity	    |Units purchased| 
| InvoiceDate	|Date of transaction |
| UnitPrice	    |Price per unit|
| CustomerID	|Unique customer ID|
| Country	    |Customer country|

## 🔥 Key Analysis Performed
🔧 Data Cleaning:
Removed canceled transactions (InvoiceNo starting with 'C').

Removed missing Customer IDs.

Created TotalPrice = UnitPrice × Quantity.

Extracted invoice month for trend analysis.