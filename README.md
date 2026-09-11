# Ecommerce Sales Analysis Dashboard (Excel)
Excel sales dashboard showing KPIs, trends, and breakdowns by category, gender, states, age group, channel, and order status.

## 📌 Project Overview

This project looks at one year of order data from Vrinda Store, an online seller that sells on multiple platforms (Amazon, Myntra, Flipkart, Ajio, Meesho, Nalli, and others). The data has 37,917 orders from over 28,437 customers across 50 states in India.

I cleaned the raw data, organized it properly, and built an interactive dashboard all inside Microsoft Excel, no other tool used. The dashboard shows total sales, total orders, average order value, total quantity sold,total customer, monthly sales trend, sales by category, sales by gender, top 5 states by sales, sales by age group, sales by order channel and order status.

## 🖼️ Dashboard Preview
<img width="1366" height="768" alt="dashboard-screenshot" src="https://github.com/user-attachments/assets/36e2bdcc-3aa1-4140-b2bf-e6cd1e36156b" />



## 🎯 Business Problem
Vrinda Store sells the same products on six different online platforms, to customers all over the country. But all the order data was in one big messy sheet, so it was hard to see how the business was really doing. The company needed simple answers to:

- What are our total sales, total orders, average order value, total quantity sold, total customer?
- Which product categories sell the most?
- Which platforms bring in the most money, and which ones are weak?
- Do men or women buy more, and which age group buys the most?
- Which states have the highest sales?
- How many orders are delivered, returned, cancelled, or refunded?

## 💡 Solution
I split that big messy sheet into separate tables, connected them by building a star schema data model, then built an interactive Excel dashboard with KPI cards, trend charts, and breakdowns by category, gender, state, age group, channel, and order status.


## 🛠️ Tools Used

- **Microsoft Excel:** Power Query(Data cleaning), Pivot Tables, Pivot Charts, DAX measures for KPI and Slicers for the interactive dashboard.

## 🔄 Project Workflow

- Cleaned the raw, messy data by fixing missing values, removing duplicates, and fixing capitalization and formatting issues using power query
- Split the big data into one fact table and five dimension tables, and also created a new dimension table for the calendar
- Connected all the tables by building a star schema data model
- Wrote DAX measures for KPI cards and built pivot tables for monthly trend, category, gender, top 5 states, age group, channel, and order status
- Built an interactive dashboard showing KPI cards, charts, and slicers

## 📐 Data Model

Built a star schema in Excel by connecting fact and dimension tables:

<img width="1366" height="768" alt="data_model_screenshot" src="https://github.com/user-attachments/assets/5aa27f2f-9abe-4ea1-bcc0-5d0647994a04" />

## 🔍 Key Insights
- Total sales is 26,022,943 from 37,917 orders and average order value is 686
- Set(13,163,924) is the best selling category
- Amazon brings in the most sales(9,212,315)
- Women buy more than men, and adults buy the most
- Delhi has the highest sales
- 93% of orders are delivered and returns, cancellations, and refunds together are under 7%

## ✅ Recommendations
- As Set is the best selling category, Always keep enough stock of it
- Grow sales on other channels too, so the business doesn't depend only on Amazon
- Run offers and ads for men, since women currently buy more
- Look at what makes Delhi sell so well, and try the same approach in other states
- Work on the 7% of orders that get returned, cancelled, or refunded


## ▶️ How to Explore

1. Download [sales_analysis_excel.xlsm](04-dashboard-file/sales_analysis_excel.xlsm)
2. Open it in Excel 
3. Go to the dashboard sheet
4. Use the slicers (Gender, Category, Status, Age Group, Channel, Month) to filter and explore

## 🤝 Contact
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanaul-habib/)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&fs=1&to=sanaul.habib12@gmail.com)
