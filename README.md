# 📊 Sales Data Analysis (2020–2022) — Python (Pandas + NumPy + Matplotlib + Seaborn)

## 🎯 Objective
This project analyzes sales performance data from **2020 to 2022** using **Python (Pandas + NumPy)**.  
The goal is to identify sales growth trends, top-performing countries, and category-wise insights for business decision-making.

---

## 📂 Dataset Overview
**File Name:** `sales_data(2020-2022).xlsx`

**Columns Include:**
- Order ID  
- Product Name  
- Category  
- Quantity  
- Sales  
- Profit  
- Country  
- Date  
- Year  

---

## 🧹 Data Cleaning
Performed using **Pandas** to ensure the dataset was ready for analysis.

**Key Cleaning Steps:**
- Removed duplicates and null values  
- Converted `Date` column to proper datetime format  
- Extracted `Year` from the `Date` column  
- Ensured numeric data types for `Sales` and `Profit`  
- Replaced missing categories with “Unknown”  

---

## 🧮 Python Analysis Steps
### 1️⃣ Dataset Overview
- Shape, columns, and missing value summary  
- Statistical summary using `describe()`  

### 2️⃣ Yearly Sales Trend
- Total sales grouped by year  
- Calculated **YoY (Year-over-Year) Growth %**

### 3️⃣ Country-Wise Performance
- Identified **Top 10** and **Bottom 10** countries by total sales  

### 4️⃣ Category-Wise Insights
- Total sales distribution by product category  

### 5️⃣ NumPy Insights
Used NumPy for additional mathematical statistics:
- Mean Sales  
- Median Sales  
- Standard Deviation  

---

## 📊 Key Findings
- **2021** recorded the highest year-over-year growth 📈  
- **Electronics & Fashion** categories dominated total revenue  
- **Top 3 countries** contributed the majority of sales share  
- **Bottom 10 countries** show potential for future marketing  

---

## 💾 Output Files (Auto-Generated)
| File Name | Description |
|------------|-------------|
| `cleaned_sales_data.csv` | Cleaned dataset ready for Power BI / Excel |
| `yearly_sales_trend.csv` | Yearly total sales and growth rate |
| `top10_country_sales.csv` | Top-performing countries summary |

---

## 📈 Power BI / Excel Dashboard (Optional)
You can import the exported CSV files to Power BI or Excel to visualize:
- Yearly Sales Trend (Line Chart)  
- Top 10 Countries (Bar Chart)  
- Category Sales (Donut Chart)  
- KPIs: Total Sales 💲, Avg Profit 📊, Growth % 🚀  

**Dashboard Title:** *“Global Sales Insights (2020–2022)”*  
**Color Theme:** Blue gradients with light background

---

## 🧰 Tools & Libraries
- **Python** 🐍  
  - Pandas  
  - NumPy
  - Matplotlib
  - Seaborn
  - Power BI 

---

## 📸 Project Screenshot
![image alt](https://github.com/Daniyal07420/Python_Sales_Data-2020-2022/blob/main/Sales_Dashboard(2020-2022)Python.png?raw=true)

---

## 🧠 What I Learned
- Real-world data cleaning & preprocessing using Pandas  
- KPI generation (Sales, Profit, Growth %)  
- NumPy for business-level statistical insights  
- Dataset preparation for Power BI dashboards  

---

## 🔗 Repository Link
📘 [GitHub Repository](https://github.com/Daniyal07420/Python_Sales_Data-2020-2022?tab=readme-ov-file)


