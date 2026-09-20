# 📊 E-Commerce Sales Analysis & Interactive Dashboard — Excel


<img width="842" height="480" alt="Screenshot 2026-09-19 191330" src="https://github.com/user-attachments/assets/c390bfd2-6d3a-4ed4-87d6-55fc4aba3e52" />












## 📌 Project Overview

This project is an end-to-end **E-Commerce Sales Analysis and Interactive Dashboard** developed using **Microsoft Excel**.

The project transforms raw transactional sales data into a structured and interactive dashboard using **data preparation, calculated columns, Excel formulas, PivotTables, PivotCharts, KPIs, slicers, and a timeline**.

The analysis focuses on **revenue, quantity sold, orders, revenue growth, customer value, product categories, cities, regions, and time-based sales performance**.

---

## 🎯 Business Objective

The objective of this project is to analyze e-commerce sales performance and provide a clear view of business performance across different dimensions.

The analysis focuses on:

- How is revenue changing over time?
- How many orders and units are being sold?
- Which product categories generate the most revenue?
- Which categories contribute the highest quantity of sales?
- Which cities generate the highest revenue?
- How does sales performance vary across regions?
- How does revenue change month-over-month?
- How do different customer categories contribute to revenue?
- How do yearly and monthly sales trends compare?
  

The dashboard is designed to help stakeholders quickly identify **sales trends, high-performing categories, geographic performance, and changes in business performance over time.**  

---

## 📂 Dataset

The raw dataset contains transactional e-commerce sales information.

### Original Columns

| Column | Description |
|---|---|
| Order ID | Unique identifier for each order |
| Order Date | Date on which the order was placed |
| Customer Name | Customer associated with the order |
| Region | Sales region |
| City | Customer/order city |
| Category | Product category |
| Product Name | Name of the product |
| Quantity | Number of units purchased |
| Unit Price | Price per unit |

---
## Analysis year ( 2023-2025)
---

## 🧹 Data Preparation & Cleaning

Before creating the dashboard, the dataset was prepared and structured for analysis.

The data preparation process included:

- Reviewing the raw dataset
- Checking for missing values
- Identifying duplicate records
- Standardizing categorical values
- Validating date fields
- Organizing month and year fields
- Checking numerical data types
- Creating calculated fields required for analysis
- Structuring the dataset for PivotTable analysis
- Validating calculated metrics before visualization

## 🧮 Calculated Columns

Additional fields were created in Excel to support the analysis.

| Calculated Field | Purpose |
|---|---|
| Month | Extracted from Order Date for monthly analysis |
| Year | Extracted from Order Date for yearly analysis |
| AOV | Calculates Average Order Value |
| Valuable Customer | Categorizes customers based on their sales value |

These calculated fields were subsequently used in PivotTables, PivotCharts, and dashboard analysis.

---

## 📊 Key Performance Indicators




<img width="752" height="97" alt="Screenshot 2026-09-19 204614" src="https://github.com/user-attachments/assets/b31fe342-2fc1-41ec-a994-75cfb6fd496c" />


Revenue: ₹593M
Orders: 5,000
Quantity Sold: 14,963 units
Revenue Growth: 48%

## 🎛️ Interactive Dashboard

The dashboard contains interactive controls that allow users to dynamically explore the sales data.

### Slicers

- Month
- City
- Category

### Timeline

- Year

Users can combine these filters to analyze specific time periods, cities, or product categories.

---


## 📈 Dashboard Visualizations

The dashboard contains seven major visualizations.

## 1. Revenue by Customer Category



<img width="277" height="245" alt="Screenshot 2026-09-19 204625" src="https://github.com/user-attachments/assets/0e4cbab4-9fa8-45a8-8239-8b1e7dbfb0db" />



Premium: 46% 

Regular: 38% 

VIP: 17%

Insight: Premium customers generate the largest share of revenue at 46%, followed by Regular customers at 38%. The business can focus on retaining Premium customers and converting more Regular customers into higher-value segments.


---

## 2. Revenue Growth by Month





<img width="312" height="245" alt="Screenshot 2026-09-19 204633" src="https://github.com/user-attachments/assets/cf6c2ab1-e362-40a8-b5a0-5c9226351981" />


Insight: The highest monthly growth was 15% in October, while the largest decline was -16% in May. This suggests strong month-to-month volatility and requires investigation into seasonality, promotions, inventory and customer demand


---

## 3. Monthly Orders & Revenue



<img width="456" height="314" alt="Screenshot 2026-09-19 204659" src="https://github.com/user-attachments/assets/c4d78c63-d0ba-420f-9f25-fc6305b95753" />



insight: Monthly revenue and order volume fluctuate throughout the year. Some months generate higher revenue despite similar order volumes, suggesting differences in Average Order Value (AOV).

Compares monthly order volume with revenue generated, providing a combined view of sales activity and revenue performance.

---

## 4. Top 10 Cities

<img width="363" height="306" alt="Screenshot 2026-09-19 204714" src="https://github.com/user-attachments/assets/3a7726a6-7488-4443-b215-afbc0c31dbec" />



The dashboard shows the leading cities contributing approximately ₹20M–₹21M each, with the top cities including:

- Ahmedabad
- Amritsar
- Lucknow
- Chandigarh
- Jaipur

Insight: Revenue is concentrated among a group of high-performing cities. These markets should be analyzed further for customer retention, order frequency and average order value.


---

## 5. Quantity by Category



<img width="343" height="428" alt="Screenshot 2026-09-20 182408" src="https://github.com/user-attachments/assets/1dd08cb4-49d8-46ad-af7d-6195c955e149" />



Insight: Furniture has the highest quantity share at 10.6%, while Beauty has the lowest at 9.1%. Product demand is relatively balanced across categories.

Shows the total quantity sold across different product categories.



---

## 6. Revenue by Category



<img width="314" height="325" alt="Screenshot 2026-09-20 182424" src="https://github.com/user-attachments/assets/5352965f-43fc-471e-8ed2-b445adb5484e" />



Home Decor contributes the highest category revenue at approximately 11.5% (₹68M), while Beauty contributes approximately 8.8% (₹52M)


---

## 7. Sales by Region



<img width="217" height="238" alt="Screenshot 2026-09-19 204745" src="https://github.com/user-attachments/assets/637092b6-87ba-4064-a161-aba5398ebb27" />


North: 27%
East: 25.43%
West: 24.47%
South: approximately 23%

Insight: Sales are fairly well distributed across regions. North contributes the largest share at 27%, while South contributes approximately 23%. No single region dominates the business.

---


## Insight

Revenue Trend: Revenue reached ₹593M, with overall revenue growth of 48%. Monthly growth was volatile, ranging from -16% to +15%.
Top Category by Revenue: Home Decor – ~11.5% of total revenue.
Top City: Ahmedabad – ~₹20M revenue.
Highest-Selling Category by Quantity: Furniture – 1,591 units (~10.6%).
Best Performing Region: North – 27% of total sales.
Highest Revenue Month: May – ~₹54M revenue.

-----  

## Business Recommendations

- Retain Premium customers because they contribute 46% of revenue.
- Convert Regular customers because they already contribute 38% of revenue.
- Investigate the -16% May decline and -13% August decline.
- Focus on high-revenue categories such as Home Decor (~11.5%) and Furniture (~11.1%).
- Investigate lower-performing categories such as Beauty (~8.8%) and Groceries (~8.9%).
- Strengthen high-performing cities while identifying opportunities in lower-revenue cities.
- Analyze regional performance beyond revenue — especially AOV, profit and customer retention.
---




# 🔄 Project Workflow

```text

Raw E-Commerce Sales Data
            ↓
 Data Preparation
            ↓
Calculated Columns
            ↓
         KPI's
            ↓
    PivotCharts
            ↓
interactive dashboard
            ↓
dashboard visualization
            ↓
       Insights
            ↓
Business Recommendations

````


----
## 🎯 CONCLUSION

The analysis shows 48% overall revenue growth, with Premium customers contributing 46% of revenue, North leading regional sales at 27%, and Home Decor generating the highest category revenue at approximately 11.5%. 
- Monthly volatility highlights opportunities to investigate the drivers of major revenue increases and declines.   

