# 📊 Superstore Sales Dashboard – Power BI

## 📌 Project Overview

The **Superstore Sales Dashboard** is an interactive **Power BI data analytics project** created to analyze sales, profit, customers, products, categories, and regional performance.

The dashboard transforms raw Superstore sales data into meaningful business insights using **Power BI, DAX, data modeling, and interactive visualizations**.

This project demonstrates practical Data Analyst skills in cleaning, analyzing, visualizing, and presenting business data.

---

## 🎯 Project Objectives

- Analyze overall sales and profit performance
- Identify the most profitable categories and sub-categories
- Analyze sales performance by region
- Understand customer segment performance
- Track monthly and yearly sales trends
- Identify top-performing products
- Create interactive Power BI dashboards
- Provide actionable business insights

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Power BI** | Dashboard development & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Calculations and measures |
| **Microsoft Excel** | Source dataset |
| **Data Modeling** | Relationships and analysis |
| **GitHub** | Project documentation & version control |

---

## 📂 Project Files

```text
Superstore-Sales-Dashboard/
│
├── 📊 SUPERSTORE SALES DASHBOARD.pbix
├── 📗 Superstore(2).xlsx
└── 📄 README.md
```

### Files Description

- **SUPERSTORE SALES DASHBOARD.pbix** – Complete interactive Power BI report.
- **Superstore(2).xlsx** – Excel source dataset used for analysis.
- **README.md** – Project documentation.

---

## 📈 Dashboard Features

### 💰 Sales Analysis
- Total Sales
- Sales by Category
- Sales by Sub-Category
- Sales by Segment
- Sales by Region

### 📊 Profit Analysis
- Total Profit
- Profit by Region
- Profit by Category
- Profit by Sub-Category
- Profit trends

### 📅 Time-Based Analysis
- Monthly Sales Trend
- Monthly Profit Trend
- Yearly Sales Analysis
- Year-over-year performance

### 🏆 Product Analysis
- Top 10 Sub-Categories by Sales
- Best-performing products
- Category performance comparison

---

## 📊 Dashboard KPIs

The dashboard provides important KPIs such as:

- **Total Sales**
- **Total Profit**
- **Total Orders**
- **Total Customers**
- **Average Sales**
- **Average Profit**

---

## 🔄 Data Analysis Workflow

```text
Raw Excel Data
      ↓
Data Import
      ↓
Power Query
      ↓
Data Cleaning & Transformation
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Interactive Visualizations
      ↓
Business Insights
```

---

## 🧹 Data Preparation

The dataset was prepared using **Power Query**.

Main activities include:

- Removing unnecessary columns
- Handling missing values
- Checking data types
- Formatting date columns
- Creating calculated fields
- Renaming columns
- Removing duplicate records
- Preparing data for analysis

---

## 🧮 DAX Measures

### Total Sales

```DAX
Total Sales = SUM(Orders[Sales])
```

### Total Profit

```DAX
Total Profit = SUM(Orders[Profit])
```

### Total Orders

```DAX
Total Orders = DISTINCTCOUNT(Orders[Order ID])
```

### Total Customers

```DAX
Total Customers = DISTINCTCOUNT(Orders[Customer ID])
```

### Average Sales

```DAX
Average Sales = AVERAGE(Orders[Sales])
```

---

## 📊 Visualizations

The dashboard uses:

- Cards
- Column Charts
- Line Charts
- Area Charts
- Bar Charts
- Donut/Pie Charts
- Slicers
- Tables
- Regional analysis

---

## 🎛️ Interactive Filters

Users can analyze the dashboard using filters and slicers such as:

- Year
- Region
- Category
- Sub-Category
- Segment
- State
- City

---

## 💡 Business Questions Answered

The dashboard can help answer:

1. Which category generates the highest sales?
2. Which region generates the highest profit?
3. Which sub-categories are the top performers?
4. Which customer segment contributes the most revenue?
5. How do sales change month by month?
6. Which products generate the highest sales?
7. Which regions have low profitability?
8. How does yearly performance change?
9. Which categories need improvement?
10. What are the major sales and profit trends?

---

## 🚀 How to Use This Project

### Step 1 – Clone the Repository

```bash
git clone https://github.com/yourusername/superstore-sales-dashboard.git
```

### Step 2 – Open the Power BI File

Open:

```text
SUPERSTORE SALES DASHBOARD.pbix
```

using **Microsoft Power BI Desktop**.

### Step 3 – Check the Dataset

The source Excel file is:

```text
Superstore(2).xlsx
```

If Power BI asks for the data source location, update the Excel file path.

### Step 4 – Explore the Dashboard

Use the slicers, filters, charts, and KPIs to interact with the report.

---

## 🖥️ Dashboard Preview

Add a screenshot of the Power BI dashboard to the repository.

Recommended structure:

```text
images/
└── dashboard.png
```

Then add:

```markdown
![Superstore Dashboard](images/dashboard.png)
```

---

## 🎓 Skills Demonstrated

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Visualization
- KPI Development
- Business Intelligence
- Exploratory Data Analysis
- Dashboard Design
- Business Reporting

---

## 👨‍💻 Author

**PRANESH S**

**Aspiring Data Analyst | Power BI | SQL | Excel**

📍 Erode, Tamil Nadu, India

---

## ⭐ Project

If you find this project useful, please consider giving the repository a ⭐ on GitHub.

---

## 📌 Future Improvements

- Add advanced DAX calculations
- Add forecasting analysis
- Add drill-through pages
- Add tooltip pages
- Add bookmarks and navigation
- Add more customer-level analysis
- Publish the dashboard to Power BI Service
- Add automated data refresh
- Add additional business KPIs

---

**⭐ Superstore Sales Dashboard | Power BI Data Analytics Project**
