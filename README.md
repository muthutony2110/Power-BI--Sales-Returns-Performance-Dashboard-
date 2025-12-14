# Optimizing Sales Data for Profit Insights  
### Power BI Data Cleaning & Profitability Analysis

## 📌 Project Overview
This project focuses on **cleaning, transforming, and optimizing sales data** to enable accurate profitability analysis and interactive reporting using **Power BI**.  
The dataset initially contained missing values, inconsistent formats, invalid text entries, and calculation issues, which were systematically resolved to deliver reliable business insights.

---

## 🎯 Project Objectives
- Clean and standardize raw sales data for accurate analysis  
- Handle missing and inconsistent numeric and date values  
- Calculate profit metrics and profitability percentages  
- Build an interactive Power BI dashboard for decision-making  
- Enable category-level, regional, and individual performance insights  

---

## 🛠️ Tools & Technologies
- **Power BI**
- **DAX (Calculated Columns & Measures)**
- **Power Query**
- **Data Modeling & Relationships**
- **Interactive Visualizations**

---

## 🧹 Data Cleaning & Preprocessing
### Preliminary Cleaning
- Removed irrelevant, duplicate, and erroneous rows
- Standardized **Order Date** by removing time components and invalid years
- Filtered dates up to valid business periods
- Capitalized text fields (Category, Sub-Category) to avoid grouping mismatches

### Numeric Column Cleaning
Created clean numeric columns by:
- Removing invalid text values (`missing`, `unknown`)
- Converting text to numeric data types  
- Columns cleaned: Sales, Quantity, Profit, Discount

---

## 🔢 Advanced Data Transformations
### Unit Value Calculations
Created DAX measures to calculate:
- Unit Sales per Product
- Unit Profit per Product
- Unit Discount per Product

These measures were used to estimate missing values reliably.

### Missing Value Handling
- Filled missing Sales, Quantity, Profit, and Discount values using unit-based logic
- Preserved original values where available
- Rounded all calculated values to **3 decimal places** for consistency

### Profit Metrics
- Created **Profit Percentage per Order**
- Created **Average Profit Percentage per Product**
- Included safe checks for division by zero and blank values

---

## 🧩 Data Modeling
- Created a **filtered analysis table** containing only relevant columns
- Removed unnecessary fields (e.g., shipping date)
- Established proper relationships between tables
- Implemented **Category → Sub-Category hierarchy** for drill-down analysis

---

## 📊 Dashboard & Visualizations
The Power BI report includes:

- **KPI Cards**: Total Orders, Total Sales, Total Profit, Total Returns  
- **Category Button Slicers** for interactive filtering  
- **Clustered Column Charts**: Sales by Category & Sub-Category  
- **Pie & Donut Charts**: Order Returns Analysis  
- **Treemap**: Profit contribution by Sub-Category  
- **Map Visual**: Country-wise Sales Distribution  
- **Table Visuals**: Detailed Sales Reporting  
- **Bar Chart**: Profit by Person (performance analysis)

---

## 🔍 Key Insights
- Cleaned data significantly improves accuracy in profitability analysis  
- Certain sub-categories contribute disproportionately to total profit  
- Returns analysis helps identify high-return product categories  
- Geographic sales mapping highlights strong and weak regions  
- Profit percentage metrics support smarter pricing and inventory decisions  

---

## 💡 Business Impact
This project enables stakeholders to:
- Monitor overall sales and profit KPIs
- Identify high- and low-performing categories
- Analyze return behavior across products
- Evaluate regional and individual contributions
- Make **data-driven business decisions** with confidence

---

## 📌 Conclusion
By following a **structured data cleaning and transformation workflow**, this project converts raw, inconsistent sales data into a reliable analytical model.  
The final Power BI dashboard delivers **clear, interactive, and actionable insights**, making it suitable for real-world business reporting and strategic planning.

---

## 👤 Author
**Muthuraj M**  
Data Analyst | AI & ML Engineer  

📧 Email: maruthumuthu04@gmail.com  

---

## 📜 License
This project is created for **learning, portfolio, and demonstration purposes**.
