# FUTURE_DS_02 - Telco Customer Churn Analysis Dashboard

## Project Overview
This project is part of the **Data Science & Analytics Track (Task 2)**.  
I built an interactive **3-page Power BI dashboard** to analyze customer churn for a telecommunications company using the classic Telco Customer Churn dataset.

The main objective was to identify key churn drivers, understand customer behavior, and provide actionable business recommendations to reduce churn.

## Dataset
- **Name**: Telco Customer Churn Dataset
- **Rows**: 7,043 customers
- **Columns**: 21 features (tenure, contract type, internet service, monthly charges, payment method, etc.)
- **Target Variable**: `Churn` (Yes/No)

## Dashboard Structure

### Page 1: Executive Summary
- Key Performance Indicators (KPIs)
- Churn Rate by Contract Type
- Churn Rate by Internet Service
- Churn Rate by Payment Method
- Churn trends by Tenure Group

### Page 2: Customer Segmentation & Deep Dive
- Tenure vs Monthly Charges Scatter Plot (colored by Churn)
- Matrix analysis of Internet Service + Bundled Services (StreamingTV, StreamingMovies, TechSupport)
- Churn Rate by Monthly Charges Bucket
- Interactive slicers for detailed filtering

### Page 3: Insights & Recommendations
- Top 5 key insights
- Actionable business recommendations with priority levels
- Summary of findings

## Tools & Technologies Used

- **Power BI Desktop**
- **Power Query** – Data cleaning, transformation, and creating custom columns (Tenure Group, Monthly Charges Bucket)
- **DAX (Data Analysis Expressions)** – Created measures for Churn Rate, segmented analysis, and comparisons
- **Data Visualization** – Cards, Bar charts, Donut charts, Scatter plots, Matrix, and Conditional formatting

## Key Insights

- Overall **Churn Rate**: **26.54%** (1,869 customers churned)
- Month-to-month contracts have **42.7%** churn rate (vs **2.8%** for 2-year contracts)
- Fiber Optic users with high monthly charges show significantly higher churn
- New customers (0–6 months) have churn rate above **53%**
- Tech Support and service bundles improve customer retention
- Electronic check payment method has the highest churn rate

## How to Use
1. Download the `.pbix` file
2. Open with **Power BI Desktop**
3. Use the slicers to interact with the dashboard
4. Navigate between the 3 pages using the tabs at the bottom

## Files Included
- `Telco Customer Churn Analysis.pbix` ← Main Power BI file
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` ← Original dataset
- `/Screenshots/` folder containing dashboard images
- `README.md`

## Skills Demonstrated
- Data cleaning and preparation using Power Query
- Advanced DAX measure creation
- Interactive dashboard design
- Business insight generation and storytelling with data
- Conditional formatting and user-friendly UX

---

**Built as part of the Future Interns Data Science & Analytics Track - Task 2**

---
