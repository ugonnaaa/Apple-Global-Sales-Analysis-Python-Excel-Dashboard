# Apple-Global-Sales-Analysis-Python-Excel-Dashboard
## Project Summary
This project analyzes global Apple product sales using a dataset from Kaggle. I used Python (Pandas) to merge multiple tables into a unified dataset, and Excel for data cleaning, creating pivot tables, and dashboard development. The goal was to extract insights on product performance, geographic sales patterns, and yearly/monthly trends.

## Dataset used 
- <a href= "https://www.kaggle.com/datasets/amangarg08/apple-retail-sales-dataset?resource=download&select=sales.csv">Dataset</a>

## Objectives
- Combine multiple relational tables into a single dataset
- Clean and format the data for analysis
- Build pivot tables to summarize global sales trends
- Develop an Excel dashboard showing key performance indicators
  
## Tools & Technologies
- Python (Pandas) — data loading, table joins, export
- Excel — data cleaning, pivot tables, dashboard
- Kaggle — dataset source

## Workflow
1. Data Loading (Python)
- Imported all four CSV files using Pandas
- Inspected column structure to ensure compatibility

2. Table Joining
- Performed explicit joins between:
- Sales ↔ Stores
- Sales ↔ Products
- Products ↔ Categories
- Created a unified dataset with sales, product, store, and category information

3. Data Cleaning
- Selected and renamed relevant columns
- Standardized date fields
- Exported the cleaned dataset as we_knows_full.csv

4. Excel Processing
Cleaned the exported data (date formatting, null checks, sorting)
Built pivot tables summarizing:
- Top product categories
- Top-performing countries
- Top-selling cities
- Monthly total sales
- Quantity sold
- Yearly sales totals

5. Dashboard Creation
Designed an Excel dashboard using:
- Pivot charts
- Slicers
- Summary tables
- Consolidated visuals into a single analytics page

## Python Script (Used for Table Joins)
- <a href= "https://github.com/ugonnaaa/Apple-Global-Sales-Analysis-Python-Excel-Dashboard/blob/main/APPLE%20RETAIL%20SALE.ipynb">Python script</a>

## Dashboard
<img width="778" height="304" alt="regional retail sales dashboard" src="https://github.com/user-attachments/assets/1c361367-2df5-4871-87b4-d4ddc1ca04e7" />

<img width="750" height="287" alt="image" src="https://github.com/user-attachments/assets/67bd50b9-0833-4cb6-b604-147319aeca21" />


## Key Insights
### Total Revenue:
- The dataset generated $22.9M+ in total sales across all regions and product categories.
- 21,824 units were sold during the analyzed period.

### Top-Selling Country
- The United States is the highest-performing market by total sales, significantly outperforming other countries.
- Other strong contributors include Australia, Japan, Canada, and China.

### Top Product Category
- Tablets emerged as the highest-grossing category.
- Smartphones and Wearables also show strong and consistent sales performance.
- Subscription Services and Streaming Devices contribute lower but steady revenue.

### City-Level Performance
- Major metropolitan cities such as Dubai, London, Los Angeles, New York, Tokyo, and Singapore rank among the top revenue-generating locations.
- Sales are concentrated in global commercial hubs, indicating strong urban demand.

### Monthly Sales Trends
- Sales remain relatively stable throughout the year.
- Notable peaks occur around September and October, suggesting seasonal or product launch-driven demand.
- June and July show slight dips compared to other months.

### Quantity Sold Trends
- Monthly unit sales follow a steady pattern with minor fluctuations.
- The highest quantities sold align closely with months of higher total revenue.

### Yearly Performance
- 2023 recorded the highest total sales.
- 2020 follows as the second-highest performing year.
- 2022 and 2024 show moderate performance.
- 2021 recorded the lowest total sales among the years analyzed.

### Product-Level Insights
- High-value products such as MacBooks, iPads, and Apple Watches significantly impact revenue despite lower unit volumes.
- Lower-priced accessories sell in higher quantities but contribute less to total revenue individually.

## Repository Structure
- APPLE RETAIL SALE.ipynb — code for loading and merging datasets
- we_knows_full.xlsx — cleaned and fully joined dataset
- regional sales dashboard.png — pivot tables and dashboard
- README.md — project documentation
