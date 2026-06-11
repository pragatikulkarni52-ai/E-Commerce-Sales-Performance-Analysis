# E-Commerce-Sales-Performance-Analysis
## Project Overview
End-to-end E-Commerce Sales Performance Analysis on 1,200 real-world order records covering 7 products, 5 order statuses, and 5 payment methods.
Built using SQL, Power BI, Python, and Excel to derive actionable business insights.

## Tools & Technologies
- *Database:* MySQL / MySQL Workbench
- *Visualization:* Microsoft Power BI (DAX Measures,Interactive Dashboard creation)
- *Programming:* Python (Pandas for data analysis, NumPy for computation, Matplotlib for visualization)
- *Spreadsheet:* Microsoft Excel (Initial data handling)
- *IDE:* Jupyter Notebook (Data cleaning EDA, and visualization)

##  Workflow

Data Cleaning (Excel) → SQL Analysis → Python (EDA) → Power BI Dashboard

## Dataset Overview
| Field | Details |
|---|---|
| Total Orders | 1,200 |
| Products | 7 (Chair, Printer, Laptop, Tablet, Monitor, Desk, Phone)  |
| Order Statuses | 5 (Delivered, Pending, Cancelled, Returned, Shipped) |
| Payment Methods | 5 (UPI, Credit Card, Debit Card, Gift Card, COD) |
| Acquisition Channels | Instagram, Google, Facebook, Referral, Email |
| Coupons Used | FREESHIP, SAVE10, WINTER15, No Coupon | 

## Key Metrics (Power BI Dashboard)
| Metric | Value |
|---|---|
| Total Revenue | ₹12,64,761.96 |
| Total Customers | 1,000 |
| Average Order Value | ₹1,053.97 |
| Return Rate | 20.58% |
| Total Orders | 1,200 |

## Power BI Dashboard Pages

### Page 1 — Sales Overview
- Total Revenue KPI Card
- Total Orders KPI Card
- Average Order Value KPI Card
- Return Rate KPI Card
- Monthly Revenue Trend (Line Chart)
- Revenue by Payment Method (Bar Chart)
- Order Status Distribution (Donut Chart)

### Page 2 — Customer Analysis
- Total Customers KPI
- Customer Acquisition by Channel (Bar Chart)
- Top Acquisition Channel: Instagram
- Revenue by Coupon Code (Bar Chart)
- Highest Revenue Coupon: FREESHIP
- Customer Segmentation by Order Frequency

### Page 3 — Product Performance
- Revenue by Product (Bar Chart)
- Top Performing Product Analysis
- Product-wise Return Rate
- Product-wise Average Order Value
- Units Sold by Product

## Key DAX Measures

These DAX measures were used to calculate key business KPIs:

Total Revenue = SUM(Sales[Revenue])
Total Orders = COUNT(Sales[Order_ID])
Average Order Value = DIVIDE([Total Revenue], [Total Orders])
Profit = SUM(Sales[Profit])

## SQL Queries

Total Revenue Calculation
Revenue by Product
Product Ranking by Revenue
Customer Acquisition by Channel
Top Acquisition Channel Identification
Revenue by Coupon Code
Return Rate by Product
Order Status Distribution
Payment Method Analysis

## Key SQL Insights

1. Top Acquisition Channel: Instagram (highest customer acquisition)
2. Highest Revenue Coupon: FREESHIP
3. Return Rate: 20.58% — identified products with highest return rates
4. Payment Preference: Analysed 5 payment methods for revenue contribution

## Python Analysis (Jupyter Notebook)

1. Data loading and exploration
2. Missing value treatment
3. Data type conversion and cleaning
4. Revenue trend visualization (Line Plot)
5. Product performance comparison (Bar Chart)
6. Payment method distribution (Pie Chart)
7. Return rate analysis (Bar Chart)
8. Customer acquisition channel visualization

## Excel Analysis

1. Data cleaning and formatting
2. Pivot Tables for revenue summary
3. Pivot Tables for product performance
4. Conditional formatting for KPI highlighting
5. Revenue calculation using SUMIF, COUNTIF formulas
6. Basic statistical analysis (Average, Min, Max)

## Business Insights

1. Instagram drives highest customer acquisition — prioritize Instagram marketing.
2. FREESHIP coupon generates highest revenue — retain and promote this coupon.
3. 20.58% return rate is high — investigate top returned products.
4. UPI and Credit Card are preferred payment methods.
5. Average Order Value ₹1,053.97 — potential for upselling higher value products.
6. Delivered orders form the majority — supply chain is efficient.
