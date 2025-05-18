# 🧮 Financials Data Cleaning & Analysis

**Author:** Moid Ahmed  
**Tools Used:** MySQL, Tableau

---

## 🧹 Data Cleaning

The dataset was first explored using `SELECT` and `LIMIT` statements to inspect the raw financial data. A staging table was created to safely perform transformations.

**Steps involved:**
- Removed dollar signs (`$`), commas, and special characters from numeric fields like `Units Sold`, `Discounts`, `Sales`, `Profit`, etc.
- Replaced problematic values like negative discounts and bracketed negatives with proper numeric formats.
- Converted text fields to appropriate numeric data types (`INT`, `DECIMAL`).
- Trimmed whitespace and standardized data.
- Parsed and converted `Date` fields into `DATE` format.
- Renamed multiple columns to PascalCase for consistency and better readability.

![image](https://github.com/user-attachments/assets/728f7420-08cf-41dc-a274-1ccc9463f2fb)

![image](https://github.com/user-attachments/assets/eb9e69ef-4608-48e4-8e80-5b1148b1f27e)

---

## 📊 Data Analysis

After cleaning, the data was analyzed to answer key business questions. Each of these insights was visualized using Tableau dashboards.

### 💰 Total Profit by Year
Calculated the total yearly profit to understand financial trends over time.

![image](https://github.com/user-attachments/assets/23039be6-9795-4677-8d2b-0acfad1f6c33)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/85063113-127a-4a3c-bc08-be6a50333e09)

### 📦 Units Sold per Product
Summed units sold per product to identify top-selling items.

![image](https://github.com/user-attachments/assets/d4239c4d-fb25-498e-9a5c-df141da1a135)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/97cc33b2-752f-493f-a9c1-75a523723c53)

### 🧾 Average Discount per Segment
Calculated average discount by customer segment to evaluate promotional strategies.

![image](https://github.com/user-attachments/assets/79282132-d3e1-4e38-9b59-0070fb538f86)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/8b273981-2a94-4475-81f1-3041153ef699)

### 🌍 Total Sales by Country
Summed total sales for each country to identify high-performing markets.

![image](https://github.com/user-attachments/assets/7fc11e43-7c0d-40a8-be16-8da79a0de3fa)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/c5d4cdd3-a9d2-4eed-9acd-a84a24762131)

![image](https://github.com/user-attachments/assets/61da5c3d-2e34-4a9d-8666-4de80bcf2073)

### 📈 Monthly Sales Trend for 2014
Analyzed month-wise sales performance for the year 2014.

![image](https://github.com/user-attachments/assets/10158d36-e766-4b55-8e20-6138b73f4997)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/8098c208-a403-42a5-a952-a02fb023d322)

### 🏭 Highest COGS Month in 2013
Identified the month with the highest Cost of Goods Sold in 2013.

![image](https://github.com/user-attachments/assets/c0ddd68a-ceac-4ec4-b007-1a01aab45e74)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/5cded458-cf33-4b95-9e74-7caa48cc047b)

### 📉 Year-over-Year Profit Growth
Computed year-over-year percentage growth in profits.

![image](https://github.com/user-attachments/assets/12d06d05-20a9-4ee6-9062-d756522758c3)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/3f311da2-7ec3-4dff-9fa3-974840620956)

### 🔍 High Discount Sales
Filtered and displayed rows where discounts were ≥ 10%.

![image](https://github.com/user-attachments/assets/35e37feb-7646-4632-bfde-d11bd76e2177)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/97ce59ef-e3a7-4875-bce4-b69028a1bedc)

### 🏆 Million-Dollar Monthly Products
Identified products that had over $1M in sales in any single month.

![image](https://github.com/user-attachments/assets/c63d08a7-01c6-4ec2-95ae-6273ee83c19d)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/6f89c714-7636-4092-8eec-d82d99f94560)

### 🎯 Gross Sales by Discount Band
Grouped gross sales by discount tiers to assess pricing effectiveness.

![image](https://github.com/user-attachments/assets/a2b54f9b-1443-4de3-b344-eccbd5f1ca90)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/1abcbea7-bb21-4501-9d68-41dbfd819386)

### 🧪 COGS by Segment and Year
Compared Cost of Goods Sold across different segments and years.

![image](https://github.com/user-attachments/assets/1104a25f-8971-4835-a436-45730f22f5af)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/e2ae0c67-505b-4bb0-ab22-e303f49800bd)

### 📊 Highest Profit Margin Product
Determined which product yielded the highest profit margin overall.

![image](https://github.com/user-attachments/assets/dbc85f8f-206e-4081-b340-54c6a17738af)

### 📈 Most Sold Product in Each Segment
Ranked products by unit sales within each segment.

![image](https://github.com/user-attachments/assets/06936f60-c085-4d43-8d54-050df4913357)

### 🏢 Segment Comparison: Small Business vs Enterprise
Compared total sales for Small Business and Enterprise segments.

![image](https://github.com/user-attachments/assets/a5653f38-d1b5-4da2-8877-91cc71f85079)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/ed3a0780-ed42-4eec-853d-6ea87d7684c1)

### 💼 Profit Margin per Row
Calculated profit margin for every row in the dataset.

![image](https://github.com/user-attachments/assets/dd185f51-975c-47ed-97bd-c220f7ef29d0)

### 💸 Total Discounts by Country
Summed the total discount given per country.

![image](https://github.com/user-attachments/assets/d22a7ceb-961f-43c9-a836-e0978ac60264)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/7ea2f33c-6d51-4f47-aac0-4bee3f6e7f14)

### 🏷️ Highest Avg Sale Price Country
Found countries with the highest average sale price.

![image](https://github.com/user-attachments/assets/f27aa7a0-6b05-41c2-9b46-7dc41720eb35)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/e4b709a9-f720-4acc-8ffe-190312696a8f)

### 🥇 Top 3 Countries by Profit
Ranked countries by total profit earned.

![image](https://github.com/user-attachments/assets/44446548-5232-4de4-9137-f591b18bdea9)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/1d5e514a-3adf-4a95-8c28-ee3d98afc77f)

### ⏳ First and Last Sale per Product
Identified the first and last sale date for each product.

![image](https://github.com/user-attachments/assets/a4854897-60c1-4cdd-8507-f106c4de23ee)

### 📊 Country Sales Ranking by Year
Ranked countries by sales within a specific year.

![image](https://github.com/user-attachments/assets/2b59dd51-0240-4274-9d9a-cf5307c06013)

-- ✅ Tableau chart created.

![image](https://github.com/user-attachments/assets/5974b102-9b32-462c-903d-3b1e008cb087)

### 📈 Month-over-Month Profit Growth
Computed month-over-month profit change to identify volatility or growth spikes.

![image](https://github.com/user-attachments/assets/aa2afe75-e9c2-40ae-bca4-038c25b7087e)

---

## 📉 Visualizations

All analytical insights were turned into **Tableau dashboards** for better understanding and storytelling, excluding the min/max date visual which was not plotted.

---

## 🧑‍💻 About the Author

**Moid Ahmed**  
A passionate data enthusiast skilled in SQL, Excel, and Tableau. This project demonstrates end-to-end capabilities in cleaning, transforming, analyzing, and visualizing business data.

---
