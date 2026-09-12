#  Pizza Sales Analysis

##  Project Overview

This project analyzes pizza sales data to evaluate overall business
performance, sales trends, customer ordering patterns, and product
performance.

The analysis was conducted using SQL Server and Microsoft Power BI.

---

##  Business Problem

The pizza business wants to understand its sales performance, identify
the strongest and weakest products and sales periods, and determine
opportunities to improve revenue and product performance.

### Main Business Question

**How can the pizza business improve sales performance by understanding
sales trends, product performance, and customer ordering patterns?**

---

## Business Questions

1. What is the overall sales performance of the business?
2. Which days of the week generate the most and fewest orders?
3. Which months have the highest and lowest order volumes?
4. Which pizza categories contribute the most to revenue?
5. Which pizza sizes generate the most revenue?
6. Which pizza categories have the highest sales volume?
7. Which pizza products are the top performers?
8. Which pizza products are underperforming?

---

##  Tools Used

- SQL Server
- Microsoft Power BI
- Excel / CSV
- GitHub

---

## 📊 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | $817.86K |
| Total Orders | 21,350 |
| Total Pizzas Sold | 49,574 |
| Average Order Value | $38.31 |
| Average Pizzas per Order | 2.32 |

---

##  Key Insights

### Overall Sales Performance

The business generated **$817.86K in total revenue** from **21,350
orders**, with an **average order value of $38.31**.

Customers purchased an average of **2.32 pizzas per order**.

### Sales Trends

**Friday** recorded the highest number of orders, while **Sunday**
recorded the lowest order volume.

**July** recorded the highest monthly order volume, while **October**
recorded the lowest.

### Category Performance

The **Classic** category generated the largest share of revenue at
**26.91%**, followed by **Supreme at 25.46%**.

The Classic category also recorded the highest sales volume, with
approximately **15K pizzas sold**.

### Size Performance

**Large pizzas** were the strongest-performing size, contributing
**45.89% of total revenue**.

### Product Performance

Top and bottom-performing pizza products were analyzed based on
**revenue, quantity sold, and number of orders**.

---

##  Business Recommendations

1. **Prepare for peak Friday demand**  
   Ensure sufficient inventory and staffing during the busiest ordering
   day.

2. **Improve Sunday performance**  
   Test targeted promotions or bundle offers to increase Sunday order
   volume.

3. **Prioritize Large pizzas**  
   Since Large pizzas contribute the highest share of revenue, maintain
   strong availability and consider Large-size bundle promotions.

4. **Maintain strong Classic pizza availability**  
   Classic pizzas lead both revenue contribution and sales volume,
   making them an important category for the business.

5. **Review underperforming products**  
   Evaluate low-performing pizzas based on revenue, quantity sold, and
   order frequency to identify opportunities for improvement.

6. **Leverage top-performing products**  
   Feature popular pizzas in promotional bundles and upselling
   opportunities.

---

## Dashboard

The Power BI dashboard provides an interactive view of:

- Overall sales KPIs
- Daily order trends
- Monthly order trends
- Revenue by pizza category
- Revenue by pizza size
- Pizza quantity sold by category
  
https://github.com/sumyyah-analyst/pizza-sales-analysis/blob/main/Pizza_Sales_Dashboard%20.png
---

##  Project Structure

```text
pizza-sales-analysis/
│
├── README.md
│
├── SQL/
│   └── pizza_sales_queries.sql
│
├── PowerBI/
│   └── Pizza_Sales_Report.pbix
│
├── Dashboard/
│   └── pizza_sales_dashboard.png
│
└── Data/
    └── pizza_sales.csv
