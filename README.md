# E-Commerce Sales Performance Analysis 2019

## Project Overview
This project analyzes E-commerce website sales performance for 2019 to identify key trends, consumer insights, and category/item performance. The goal is to provide an overview of a year’s worth of online sales and derive actionable insights for optimizing product offerings, marketing strategies, and inventory management. The final dashboard visualizes the data in an easy-to-understand format.

## Tools Used
- **Microsoft Excel**: Data cleaning, pivot tables, charts, and dashboard creation.

## Data Source
The dataset is fictional and sourced from Kaggle. You can access it [here](https://www.kaggle.com/datasets/naofilahmad/sales-datset-product-sample).

## About the Dataset
The dataset is a collection of raw E-commerce sales data from the year 2019. It contains 13 columns:
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

With 178,437 orders placed throughout the year, the dataset was messy and required significant cleaning before meaningful analysis could take place. After cleaning, the data provided valuable insights into consumer purchasing behavior.

## Project Workflow
1. **Data Cleaning**:
   - Removed blanks and unnecessary columns.
   - Refined product categories.
   - Found and corrected spelling errors.
   - Eliminated unwanted spaces and standardized formats (numbers, dates).
   - Distinguished a same city name in two different states.
   - Extracted additional columns such as city, state, and zip codes from the purchase address.
   - Removed hard-coded cells to ensure data consistency.

2. **Pivot Tables**:
   - Created summary tables for revenue and quantity sold across categories, products, cities, states, months, and time periods.

3. **Dashboard**:
   - Designed a professional dashboard with the following charts:
     - **Revenue by Product Category** (Bar Chart)
     - **Revenue Trends by Month** (Line Chart)
     - **Revenue Distribution by Time of Day** (Pie Chart)
     - **State Performance: Revenue vs. Quantity Sold** (Combo Chart)

## Key Insights

### **1. Product Performance**
- **Top Product Category**:  
  *Laptops and Computers* generated the highest revenue share of all categories, accounting for just over **35% of total revenue**. *Phones* followed as the second-largest contributor, contributing just under **26% of total revenue**. Despite these two categories representing only **11% of total unit sales**, they accounted for over **61% of total revenue**, emphasizing that high-value electronics are the primary revenue drivers for the business.

- **Bottom Product Category**:  
  At the other end of the spectrum, *Batteries* accounted for the lowest revenue share at just **0.58%**, followed by *Charging Cables* at **1.84% of total revenue**. However, these categories made up over **50% of total unit sales**, demonstrating the high demand for inexpensive accessory items, which are essential for complementing high-value electronics.

- **Top Products**:  
  The *MacBook Pro Laptop* was the highest revenue-generating product, contributing just over **23% of total revenue**, followed by the *iPhone*, which accounted for nearly **14%**. Together, these two products represented only **5.5% of total unit sales** but drove a remarkable **37% of total revenue**, highlighting the immense demand for popular Apple products.

- **Bottom Products**:  
  The five lowest-performing products in terms of revenue share were:  
  - *AAA Batteries (0.27%)*  
  - *AA Batteries (0.31%)*  
  - *Wired Headphones (0.71%)*  
  - *USB-C Charging Cable (0.83%)*  
  - *Lightning Charging Cable (1.01%)*  
  Collectively, these products accounted for just **3.13% of total revenue**. However, they represented over **60% of total unit sales**, reiterating their role as high-demand, low-cost essentials purchased frequently to support premium electronics.

### **2. Time-Based Trends**
- **Revenue by Month**:  
  - **December** was the most profitable month, generating **$4,613,443.34**, largely due to holiday shopping and promotions.  
  - The **first quarter** of the year (January - March) had the lowest revenue share, accounting for **19.31%** of total revenue, with January contributing the least at **$1,822,256.73**, likely due to a post-holiday slowdown.  
  - The **second quarter** (April - June) showed a slight increase in revenue, contributing **26.44%** of the annual total.  
  - The **third quarter** (July - September) saw a slight decline, accounting for **20.26%**, indicating a typical summer slowdown.  
  - The **fourth quarter** (October - December) was the most profitable, with a revenue share of **33.5%**, driven by back-to-school shopping and the holiday season.

- **Revenue by Time of Day**:  
  - **Afternoon hours (12 PM - 5 PM)** generated the highest revenue, contributing **36%** of the total, as most customers likely placed orders during lunch breaks or leisure time.  
  - **Evening hours (5 PM - 10 PM)** were the second busiest, accounting for **34%** of revenue, as customers shopped from home after work.  
  - **Morning hours (6 AM - 12 PM)** contributed **24%** and showed steady performance throughout the year.  
  - **Night hours (12 AM - 6 AM)** had the lowest revenue share at just **6%**, reflecting minimal activity during typical sleep hours.

### **3. Geographic Insights**
- **Top Performing States**:  
  - *California* dominated sales, contributing **$13,714,774.71** in revenue and **83,528 units sold**, accounting for nearly **40% of total revenue and units sold**.  
  - *New York* ranked second with **$4,664,317.40** in revenue and **27,932 units sold**, followed closely by *Texas* with **$4,587,557.15** in revenue and **27,883 units sold**.  
  - Together, these three states accounted for a significant **66.59% of total revenue**, showcasing their high, tech-savvy populations and roles as key markets.

- **Bottom Performing States**:  
  - *Maine* contributed just **$449,758.27** in revenue and **2,750 units sold**, making up only **1.3% of total revenue and units sold**.  
  - *Oregon* and *Washington* performed slightly better, accounting for a combined **13% of revenue and units sold**, driven by a smaller, less tech-savvy population base and fewer transactions.

- **Top Performing Cities**:  
  - *San Francisco, CA* led all cities, generating **$8,262,203.91** in revenue.  
  - *Los Angeles, CA* ranked second with **$5,452,570.80**, followed by *New York, NY* at **$4,664,317.43**.  
  - These three cities alone contributed **53.29% of total revenue**, highlighting the dominance of major urban centers.

- **Bottom Performing Cities**:  
  - As the only city in *Maine*, *Portland, ME* ranked as the lowest-performing city in revenue and units sold.  
  - *Austin, TX* and *Portland, OR* followed, with these three cities collectively accounting for **12% of revenue and units sold**, reflecting their smaller market size compared to top-performing cities.

---

## Recommendations

### **Marketing**
1. Focus marketing campaigns on high-revenue regions like *California*, *New York*, and *Texas*, where there is strong demand for high-value electronics.
2. Promote premium products like *MacBook Pro Laptops* and *iPhones* to sustain and grow revenue from high-ticket items.
3. Run targeted campaigns during the **fourth quarter** (October - December), emphasizing holiday shopping and back-to-school sales.
4. Leverage email campaigns during **Afternoon and Evening hours**, when customers are most likely to shop.

### **Inventory**
1. Ensure adequate stock of premium electronics (e.g., laptops and phones) in top-performing regions to meet demand.
2. Increase inventory of high-demand, low-revenue accessories (e.g., batteries, charging cables) to capitalize on frequent orders.
3. Optimize inventory in low-performing states and cities to avoid overstocking while maintaining availability for smaller markets.
