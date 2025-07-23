 # E-Commerce Sales Performance Analysis (2019)

## 📊 Project Overview

This project analyzes E-commerce website sales performance for 2019 to identify key trends, consumer insights, and category/item performance. The goal is to provide an overview of a year’s worth of online sales and derive actionable insights for optimizing product offerings, marketing strategies, and inventory management.

## 🛠 Tools Used

- **Microsoft Excel**: Data cleaning, pivot tables, charts, and dashboard creation  
- **Power BI**: Interactive dashboard with advanced visualizations and filtering capabilities

---

## 📁 Data Source

The dataset is fictional and sourced from Kaggle. You can access it [here](https://www.kaggle.com/datasets/itsnahm/ecommerce-sales-data-in-2019?resource=download).

---

## 📂 Files Included

### Excel Workflow

1. **`raw_data.xlsx`**  
   - Original dataset containing all raw E-commerce transactions  
2. **`cleaned_data.xlsx`**  
   - Cleaned and structured version of the data for analysis  
3. **`pivot_tables.xlsx`**  
   - Includes dynamic summary tables with slicers  
4. **`dashboard.xlsx`**  
   - Final Excel dashboard with visualizations  
5. **`/Documentation/Data_Cleaning_Screenshots`**  
   - Screenshots documenting the Excel cleaning process

### Power BI Dashboard

6. **`ecommerce_2019_dashboard.pbix`**  
   - Power BI file with interactive visualizations  
7. **`dash_screenshot.png & map_screenshot.png`**  
   - Screenshots of the Power BI dashboard for preview

> 🧭 **To view the Power BI Dashboard:**  
> Download the `.pbix` file and open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/).

---

## 📌 Dataset Overview

The dataset contains 178,437 rows with the following columns:

- Order ID  
- Product Category  
- Product  
- Quantity Ordered  
- Price Each  
- Order Date  
- Purchase Address  
- Month  
- Sales  
- City  
- Hour  
- Time of Day  

After cleaning and processing, the dataset yielded deep insights into purchasing trends, geography-based performance, and sales cycles.

---

## 🔄 Project Workflow

### 🔹 Data Cleaning (Excel)

- Removed blanks and unnecessary columns  
- Corrected spelling errors and formatting inconsistencies  
- Extracted City, State, and ZIP from address fields  
- Distinguished cities with the same name in different states  
- Eliminated hard-coded values to standardize structure  

### 🔹 Pivot Tables (Excel)

- Created summary views for:  
  - Revenue by Category, Product, State, City, and Month  
  - Quantity Sold by Product and Region  
  - Time-of-day purchase patterns  

### 🔹 Dashboards

#### ✅ Excel Dashboard Includes:

- Bar chart: Revenue by Product Category  
- Line chart: Revenue Trends by Month  
- Pie chart: Revenue by Time of Day  
- Combo chart: Revenue vs Quantity by State  

#### ✅ Power BI Dashboard Includes:

- KPI Cards: Total Revenue, Orders, Units Sold  
- Bar chart: Top 10 Products by Revenue  
- Line chart: Monthly Revenue Trends  
- Map: Geographic Revenue Distribution (by City)  
- Interactive filters for detailed insights  

---

## 💡 Key Insights

### 📦 Product Performance

- **Top Category**: Laptops & Computers (35% revenue)  
- **Top Products**:  
  - MacBook Pro (23% of total revenue)  
  - iPhone (14% of total revenue)  
- **Low Revenue, High Volume**:  
  - AAA/AA Batteries, Charging Cables — over 50% of total unit sales but only 3% of revenue  

### ⏰ Time-Based Trends

- **Peak Month**: December ($4.6M)  
- **Slowest Month**: January  
- **Most Active Hours**:  
  - Afternoon (36%) and Evening (34%)  
  - Least active: Night (6%)  

### 🌍 Geographic Insights

- **Top States by Revenue**:  
  - California ($13.7M), New York, Texas  
- **Top Cities**:  
  - San Francisco, Los Angeles, New York City  
- **Lowest Revenue**: Portland, ME  

---

## 📈 Recommendations

### 🎯 Marketing

- Focus ad spend on top states: California, NY, TX  
- Promote premium electronics (MacBook, iPhone)  
- Schedule campaigns during Q4 and peak shopping hours  

### 🏪 Inventory

- Stock more premium electronics in high-revenue areas  
- Maintain accessory inventory to fulfill high-volume, low-cost demand  
- Avoid overstock in low-performing cities  

---

## 📎 Notes

- All Excel files are in `.xlsx` format  
- Power BI file is `.pbix` and must be opened with Power BI Desktop  
- All data and analysis are for educational purposes only  



