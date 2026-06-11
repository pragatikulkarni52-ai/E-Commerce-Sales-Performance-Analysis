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

## Dataset Overview
| Field | Details |
|---|---|
| Total Orders | 1,200 |
| Products | 7 |
| Order Statuses | 5 (Delivered, Pending, Cancelled, Returned, Processing) |
| Payment Methods | 5 (UPI, Credit Card, Debit Card, Net Banking, COD) |
| Acquisition Channels | Instagram, Google, Facebook, Referral, Direct |
| Coupons Used | FREESHIP, SAVE10, FLAT50, WELCOME, None | 

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
