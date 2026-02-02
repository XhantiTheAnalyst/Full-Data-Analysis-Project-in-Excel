# Full-Data-Analysis-Project-in-Excel
Excel practice project demonstrating end-to-end data workflow: data cleaning, analysis, and visualization. Uses a simulated dataset for educational and portfolio purposes.

# 📊 Global Wealth Analysis in Excel

## Project Overview
This project demonstrates an **end-to-end data analysis workflow in Microsoft Excel** using a publicly available dataset of high-net-worth individuals worldwide. The analysis focuses on understanding wealth distribution, demographic patterns, and geographic concentration among the world's wealthiest individuals.  

The project is intended **strictly for educational and portfolio purposes**, using publicly available data to showcase Excel skills in data cleaning, transformation, analysis, and visualization.

---

## Data Cleaning & Transformation
- **Maintained data integrity** by creating a backup of the original raw dataset  
- **Removed duplicates** to ensure accurate analysis  
- **Standardized categorical values:** converted `Gender` column from `M`/`F` to `Male`/`Female`  
- **Derived Age:** aggregated `BirthYear`, `BirthMonth`, and `BirthDay` to create a Date of Birth column, then calculated age using the `YEARFRAC` function  
- **Cleaned GDP data:** removed `$` symbols and converted values to numeric currency type for accurate analysis  
- Verified other columns for consistency and proper formatting  

---

## Data Analysis
- **Descriptive statistics:** used Excel Data Analysis Tool to calculate mean, median, min, max, and standard deviation for numeric columns including Net Worth, Age, and GDP  
- **Pivot tables:**  
  1. **Top 10 wealthiest individuals** – sorted descending by Net Worth  
  2. **Wealth distribution by age group** – counts of individuals in each age range  
  3. **Geographic distribution of wealth** – counts by country  

---

## Data Visualization
- **Clustered column charts** corresponding to each pivot table:  
  1. Top 10 wealthiest individuals  
  2. Wealth distribution by age group  
  3. Geographic distribution by country  
- Charts highlight patterns in **wealth concentration, demographic breakdowns, and regional distribution**  
- Visuals support **clear and actionable insights** without relying on a full dashboard  

---

## Tools & Techniques Used
- Microsoft Excel: formulas, pivot tables, charts  
- Data cleaning and feature transformation  
- Descriptive statistics and exploratory data analysis  
- Data visualization for storytelling and insight communication  
