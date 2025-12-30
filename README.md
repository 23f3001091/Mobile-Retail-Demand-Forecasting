# Mobile-Retail-Demand-Forecasting
A data analysis project optimizing inventory management for a local mobile retailer (Aradhya Enterprises). Utilized Excel and SARIMA modeling on 15 months of sales data to forecast demand, classify stock (ABC Analysis), and reduce holding costs.

## Project Overview
This project analyzes **real-world mobile retail sales data** to uncover sales patterns, revenue drivers, and inventory insights.  
The objective was to apply **data analytics and time series forecasting** techniques to support **business decision-making** in a retail context.

The analysis covers:
- Brand-wise and category-wise performance
- Accessory vs device contribution
- Monthly sales trends
- Revenue forecasting using SARIMA
- Correlation analysis between quantity, pricing, and revenue

---

## Business Problem
A mobile retail store wanted to understand:
- Which brands and products drive most of the revenue
- How accessories contribute compared to devices
- Monthly demand patterns and seasonality
- Whether future revenue trends can be forecasted
- The relationship between sales quantity, unit price, and total revenue

These insights are critical for **inventory planning, pricing strategy, and sales optimization**.

---

## Dataset Description
- **Time Period:** January 2024 – April 2025  
- **Data Source:** Real retail sales records  
- **Granularity:** Transaction-level data  

### Key Columns:
- Date  
- Product Name  
- Category (Device / Accessory)  
- Brand Name  
- Quantity  
- Unit Price  
- Total Revenue  
- Month-Year  

---

## Data Cleaning & Preparation
Data preprocessing was performed using **Excel and Python**:
- Removed non-standard header rows during ingestion
- Standardized column names to handle whitespace issues
- Filtered numeric columns for statistical analysis
- Aggregated data for monthly and brand-level insights

This ensured the dataset was **clean, consistent, and analysis-ready**.

---

## Analysis Performed

### ABC (Pareto) Analysis
- Identified high-revenue brands contributing to the majority of sales
- Observed Pareto behavior where a small set of brands drive most revenue

### Brand-wise Revenue Performance
- Compared total revenue across major smartphone brands
- Highlighted top-performing and underperforming brands

### Accessory Type Analysis
- Analyzed sales volume and revenue contribution of accessories
- Screen guards, chargers, and phone covers showed high demand

### Device vs Accessory Contribution
- Devices contribute **~91% of total revenue**
- Accessories contribute **~9%**, but generate higher transaction frequency

### Monthly Sales Trend Analysis
- Identified seasonal fluctuations in sales quantity and revenue
- Highlighted peak and low-demand periods

### Correlation Analysis (Heatmap)
- Strong positive correlation between **Quantity and Total Revenue**
- Moderate correlation between **Unit Price and Revenue**
- Weak correlation between **Quantity and Unit Price**

This validates common retail sales dynamics.

### Revenue Forecasting (SARIMA)
- Applied **SARIMA** for time series forecasting
- Forecasted short-term revenue trends
- Demonstrated practical forecasting for retail planning

---

## Key Visualizations
All insights are supported by visualizations available in the `/visuals` folder:
- ABC Pareto Chart  
- Brand-wise Revenue Chart  
- Accessory Sales Distribution  
- Device vs Accessory Revenue Share  
- Monthly Sales Trends  
- Correlation Heatmap  
- SARIMA Revenue Forecast  

---

## Key Insights
- A small number of brands dominate overall revenue
- Accessories drive sales volume but contribute less to revenue
- Monthly seasonality affects sales patterns
- Quantity is the strongest driver of revenue
- Forecasting indicates fluctuating but recoverable revenue trends

---

## Business Recommendations
- Focus inventory planning on **high-revenue brands**
- Use accessories for **bundling and upselling**
- Plan promotions during low-demand months
- Optimize pricing for high-volume products
- Use revenue forecasts to guide short-term inventory decisions

---

## Tools & Technologies
- **Microsoft Excel** – Data cleaning, pivot tables, charts  
- **Python (Google Colab)** – Pandas, Matplotlib, Seaborn  
- **Time Series Forecasting** – SARIMA  
- **Statistical Analysis** – Correlation analysis  

---

## Academic Report
The detailed academic version of this project is available in the `/report` folder for reference.

---
