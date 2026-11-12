# Sales Performance Analysis Dashboard (Power BI)

## Project overview
Analyze a fictional retail company's 2025 sales data to understand revenue, profit, product mix, regional performance and monthly trends. The dataset is synthetic and created for portfolio practice; do not present it as real company data.

## Tools
- Microsoft Power BI Desktop
- CSV dataset (`sales_data.csv`)
- Power Query for data checks and transformations
- DAX for KPIs

## Dataset
1,200 fictional order records covering 1 Jan–31 Dec 2025.
Fields include Order_ID, Order_Date, City, Region, Customer_ID, Product, Category, Quantity, Unit_Price, Discount, Sales, Cost and Profit.

## Build the report
1. Open Power BI Desktop.
2. Select **Get data > Text/CSV** and import `sales_data.csv`.
3. In Power Query, set Order_Date to Date; set Sales, Cost, Profit and Unit_Price to Decimal Number; set Quantity to Whole Number; set Discount to Decimal Number.
4. Select **Close & Apply**.
5. Create the DAX measures from `DAX_Measures.txt`.
6. Create the visuals listed in `Dashboard_Layout.txt`.
7. Add slicers for Year, Region and Category.
8. Save as `Sales_Performance_Analysis.pbix`.

## Suggested business questions
- Which region contributes the most sales and profit?
- Which products generate the highest revenue?
- How do sales and profit change month by month?
- What is the average order value?
- Which categories have lower profit margins?

## Quality checks
- Confirm Order_ID is unique.
- Check for blank values.
- Compare total Sales with the sum of row-level Sales.
- Check that Profit = Sales - Cost.
- Explain that this is synthetic practice data in your portfolio.

## Portfolio deliverables
- `sales_data.csv`: source dataset
- `DAX_Measures.txt`: measures
- `Dashboard_Layout.txt`: recommended report layout
- `Resume_Project_Description.txt`: honest resume wording
- `README.md`: project documentation

## Important
This package contains the dataset and complete build guide, not a pre-rendered `.pbix` file. You must create and save the Power BI report in Power BI Desktop before claiming the dashboard is completed.


## Ready-made Excel dashboard
`Sales_Analysis_Ready_Dashboard.xlsx` includes a prebuilt overview dashboard, KPI cards, charts, raw data, and summary tabs. You can review this immediately or import the CSV into Power BI to recreate the report there.
