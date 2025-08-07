📊 Business Performance Dashboard – Financial Sales Analysis
🚀 Project Objective
The goal of this project is to design a fully interactive and insightful Power BI dashboard to help business stakeholders monitor performance, track KPIs, and make data-driven decisions from financial sales data.

📁 Dataset

Source: `Financials.csv` (Uploaded)
Type: Financial Sales Data across multiple countries, products, and segments
Fields: Sales, Profit, Country, Segment, Product, Discount, Month


 🧹 Step-by-Step Data Cleaning (in Excel)

  ✅ 1. Remove Blank Rows and Columns
- Deleted any fully blank rows and columns to ensure clean structure.

  ✅ 2. Convert Currency Columns to Numbers
  Removed currency symbols (like `$`) from `Sales` and `Profit` columns.
  Used Excel formula:
    =VALUE(SUBSTITUTE(A2, "$", ""))

✅ 3. Fill Missing Values
Filled missing values in Discount column with 0 using:
Go To Special > Blanks > Enter 0 > Ctrl + Enter

✅ 4. Standardize Date/Time
Ensured Month column had consistent values (e.g., full month names).
Optionally split or extracted Month Name from Date if needed.

✅ 6. Removed Duplicates
Applied Remove Duplicates on key columns like Order ID, Product, etc.


📊 Power BI Dashboard Overview

🛠️ Tools Used
Power BI Desktop
Microsoft Excel (for initial cleaning)

Data Source: CSV (Financial_Sales_Data.csv)

✅ Dashboard Name:
Business Performance Insights – Financial Sales Dashboard

📌 Key Features:
🎯 KPI Cards	Displays Total Sales, Total Profit, and Profit Margin in real-time
📈 Time-Series Trend	Monthly Profit Trend using line chart
🧩 Slicers & Filters	Dynamic filters for Country, Segment, and Product
📊 Sales vs Profit View	Bar chart comparing Sales and Profit by Country
📌 Discount Analysis	Scatter chart showing discount impact across regions
🍩 Profit by Segment	Donut chart representing contribution by different segments
🌍 Geographic Sales	Bar chart for sales across countries
🎨 Consistent Theme	Professional, clean color palette for readability and branding

🔍 Insights Gained

USA generates the highest revenue and profit.
Enterprise and Government are the top-performing segments.
Higher discounts do not always correlate with higher profits.
A clear seasonal dip in profits over time is visible.

📚 Learning Outcomes

Mastered Power BI Dashboard design principles
Understood the impact of data cleaning and transformation
Practiced using visual interactivity and KPIs
Gained hands-on experience in business communication through dashboards

🖼️ Dashboard Preview
Business Performance Insights – Financial Sales Dashboard

📂 Folder Structure

├── Financial_Sales_Data.csv
├── Dashboard.pbix
├── Screenshot.png
└── Finacial_sales_Data.pptx
└── README.md

