# OIBSIP
Data Analytics Internship -L1-Task-Retail-Sales
**# 🛒 Retail Sales EDA Dashboard | Power BI

**Oasis Infobyte (OIBSIP) Data Analytics Internship – Level 1, Task 1**

An interactive 3-page Power BI dashboard that turns raw retail transactions into insights on **sales performance, customer behavior, and product demand**.

![Dashboard Preview](screenshots/Sales_Overview.png)

🎥 **Demo Video:** [Watch here](YOUR_VIDEO_LINK)

---

## 🎯 Business Problem

A retail business wants to know: *which products drive revenue, who buys them, and how price affects purchase quantity*, so it can plan inventory, marketing, and pricing better.

## 🛠️ Tools

Power BI · Power Query · DAX · GitHub

## 📊 Dataset

- **Records:** [X] transactions | **Period:** [start] – [end]
- **Columns:** Transaction ID, Customer ID, Date, Gender, Age, Product Category, Quantity, Price per Unit, Total Amount

## 🧹 Data Preparation (Power Query)

- Checked for null values and duplicates: [X found / none found]
- Set correct data types (Date, Whole Number, Decimal)
- Created **Age Group** column: 18–25, 26–35, 36–45, 46–55, 56+
- Created Month/Year columns from Date for trend analysis

## 🧮 Key DAX Measures

```DAX
Total Sales = SUM(Sales[Total Amount])
Average Sales = AVERAGE(Sales[Total Amount])
Max Sales = MAX(Sales[Total Amount])
Total Quantity = SUM(Sales[Quantity])
```

---

## 📈 Dashboard Pages

### Page 1 – Sales Overview
Total & average sales by category, monthly sales trend, quantity sold, KPI cards.
![Sales Overview](screenshots/Sales_Overview.png)

### Page 2 – Customer Analysis
Gender split, customers and sales by age group, average sales and quantity by gender.
![Customer Analysis](screenshots/Customer_Analysis.png)

### Page 3 – Product & Business Insights
Top 10 products, revenue by category, price vs quantity scatter, correlation view.
![Product Insights](screenshots/Product_Business_Insights.png)

---

## 💡 Key Findings

1. **[Category]** generated the highest revenue: **[X]%** of total sales.
2. **Age group [X–Y]** contributed the most sales ([amount]).
3. **[Male/Female]** customers had a higher average order value ([X] vs [Y]).
4. Sales peaked in **[month]** and dropped in **[month]**.
5. Price vs Quantity: [e.g., no strong relationship / higher-priced items sold fewer units].
6. Correlation: **Total Amount** is strongly tied to **Quantity** and **Price**; **Age** shows [weak/no] relationship with spending.

## 🚀 Recommendations

- **Prioritize [Category]** for inventory and promotions, since it drives the largest revenue share.
- **Target the [age group]** segment with personalized offers.
- **Plan stock ahead of [peak month]** to avoid stock-outs.
- **Test bundle/discount offers** on [low-performing category] to lift quantity.

## ⚠️ Limitations

- Dataset covers only [period] and [X] transactions, so seasonality can't be confirmed.
- No profit/cost data, so analysis is revenue-based, not profit-based.
- Correlation does not imply causation.

## 📂 Project Structure

```text
DataAnalytics-L1-Task1-Retail-Sales/
├── OIBSIP_Retail_Sales_EDA.pbix
├── dataset.csv
├── README.md
└── screenshots/
```

## 👤 Author

**Montu Mali** · Aspiring Data Analyst
🔗 [LinkedIn](YOUR_LINK) · 💻 [GitHub](YOUR_LINK)**
