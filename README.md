# Apple-Global-Sales-Analysis-Python-Excel-Dashboard
## Project Summary
This project analyzes global Apple product sales using a dataset from Kaggle. I used Python (Pandas) to merge multiple tables into a unified dataset and Excel for data cleaning, pivot tables, and dashboard creation. The goal was to extract insights on product performance, geographic sales patterns, and yearly/monthly trends.

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
- <a href= "https://www.kaggle.com/datasets/amangarg08/apple-retail-sales-dataset?resource=download&select=sales.csv](https://github.com/ugonnaaa/Apple-Global-Sales-Analysis-Python-Excel-Dashboard/blob/main/APPLE%20RETAIL%20SALE.ipynb">Python script</a>

## Dashboard
<img width="795" height="274" alt="regional sales dashboard" src="https://github.com/user-attachments/assets/a6d7d0de-5633-4229-8b79-3afa97bbde5f" />

## Key Insights
- Wearables, Smartphones, and Accessories are among the highest-selling categories
- The USA, Japan, China, Germany, and the UK contribute the largest sales volumes
- Cities like Dubai, London, Los Angeles, and Tokyo dominate sales performance
- Monthly sales trends show strong Q3–Q4 activity
- Quantity sold remains consistent year-to-year with slight growth

## Repository Structure
- APPLE RETAIL SALE.ipynb — code for loading and merging datasets
- we_knows_full.csv — cleaned and fully joined dataset
- regional sales dashboard.png — pivot tables and dashboard
- README.md — project documentation
