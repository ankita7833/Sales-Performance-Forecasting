# Sales Performance & Forecasting Analysis

## Python & Data Science Internship Assessment

This project performs an end-to-end analysis of the Superstore retail sales dataset.

## Project Objectives

- Clean and inspect the retail sales dataset
- Handle missing values and duplicates
- Perform exploratory data analysis
- Analyze category-wise and region-wise sales
- Identify top-selling products
- Generate statistical summaries
- Build and evaluate sales forecasting models
- Provide actionable business recommendations

## Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Analysis Performed

### Exploratory Data Analysis

The project includes:

1. Monthly Sales Trend
2. Sales by Product Category
3. Sales by Region
4. Correlation Heatmap
5. Top 10 Products by Sales
6. Actual vs Predicted Monthly Sales

### Statistical Analysis

Key Sales statistics:

- Mean: 230.77
- Median: 54.49
- Standard Deviation: 626.65
- Minimum: 0.444
- Maximum: 22,638.48

### Machine Learning

Two regression models were evaluated:

| Model | RMSE | R² |
|---|---:|---:|
| Linear Regression | 23,619.29 | 0.0332 |
| Random Forest Regression | 16,094.10 | 0.5511 |

The Random Forest model performed better and was selected as the final model.

## Key Findings

- Technology generated the highest category sales: 827,455.87.
- West was the highest-performing region: 710,219.68.
- Canon imageCLASS 2200 Advanced Copier was the top-selling product: 61,599.82.
- November 2018 recorded the highest monthly sales: 117,938.15.

## Business Recommendations

- Focus inventory and promotions on Technology products.
- Investigate opportunities to improve South-region performance.
- Prioritize high-performing products.
- Prepare inventory and marketing for high-demand periods.
- Improve forecasting by incorporating additional business variables.

## Project Structure

```text
Sales-Performance-Forecasting/
│
├── data/
│   └── train.csv
│
├── outputs/
│   ├── monthly_sales_trend.png
│   ├── category_sales.png
│   ├── region_sales.png
│   ├── correlation_heatmap.png
│   ├── top_10_products.png
│   └── actual_vs_predicted.png
│
├── report/
│   └── Sales_Performance_Forecasting_Report.pdf
│
├── Sales_Performance_Forecasting.ipynb
├── create_report.py
└── README.md
