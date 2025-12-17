# Company Funding & Layoff Trend Analysis 📊

## Description
This project analyzes layoffs and funding trends across companies using SQL and Power BI.  
The goal is to understand the market by countries, companies, and stages, and identify patterns in funding and layoffs. 🌍

## Dataset
The dataset contains the following information:
- `company` – Company name  
- `country` – Country of operation  
- `industry` – Industry sector  
- `stage` – Company stage (e.g., early, growth, late)  
- `funds_raised` – Total funds raised by the company  
- `percentage_laid_off` – Percentage of employees laid off  
- `date` – Date of the record  

The database was **cleaned and prepared manually using SQL**.

## Data Cleaning Process 🧹
Steps performed to prepare the dataset:
1. Removed all duplicate records  
2. Standardized data formats (dates, numeric values)  
3. Removed or restored null/blank values  
4. The cleaned version is available in this repository as:  
   `project_layoffs_staging2.sql`  

After cleaning, the data was imported into Power BI for visualization.

## Power BI Dashboards 📈
The dashboards include:
- Combined line and column chart showing funds raised and layoffs by year  
- Layoffs by year  
- Donut chart displaying funds raised per company  
- Scatter chart: X-axis = funds raised, Y-axis = total layoffs, bubble size = percentage of layoffs  
- Map showing funds raised by country  

These visualizations provide insights into the relationship between funding and layoffs across companies and stages.

## Tools & Technologies 🛠️
- SQL (MySQL)  
- Power BI  
- Data Cleaning & Analysis  

## Files in Repository
- `Company_Funding_Layoff_Dashboard.pbix` – Power BI dashboard file  
- `Visualization.png` – Dashboard screenshot  
- `project_layoffs_staging2.sql` – Cleaned MySQL database  

## Key Insights 💡
- Layoffs are more common in early-stage companies  
- Companies with higher funding generally experience fewer layoffs, both in total numbers and percentage  
