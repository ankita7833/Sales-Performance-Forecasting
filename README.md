# Sales Performance & Forecasting Analysis

## Python & Data Science Internship Assessment

This project is based on the Superstore retail sales dataset.

The main aim of this project is to understand the sales performance of the business, find useful patterns in the data, and build a basic model to predict monthly sales.

## Objectives

The main objectives of this project are:

- Load and understand the sales dataset
- Check and clean the data
- Handle missing values and duplicate records
- Convert data into suitable formats
- Perform exploratory data analysis
- Study sales by month, category, and region
- Find the top-selling products
- Calculate basic statistical values
- Build a sales forecasting model
- Compare model predictions with actual sales
- Give some business recommendations based on the analysis

## Tools Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

The project uses the Superstore Sales Dataset provided for the internship assessment.

The dataset used in this project is:

`data/train.csv`

## Data Cleaning

The dataset was first loaded and inspected.

The following checks were performed:

- Checked the number of rows and columns
- Checked data types
- Checked missing values
- Checked duplicate records
- Converted date columns into proper date format
- Handled the missing values found in the dataset

## Exploratory Data Analysis

The following visualizations were created:

1. Monthly Sales Trend
2. Sales by Product Category
3. Sales by Region
4. Correlation Heatmap
5. Top 10 Products by Sales
6. Actual vs Predicted Monthly Sales

The charts are saved in the `outputs` folder.

## Statistical Summary

The main statistics for Sales are:

- Mean Sales: 230.77
- Median Sales: 54.49
- Standard Deviation: 626.65
- Minimum Sales: 0.444
- Maximum Sales: 22,638.48

The mean is higher than the median, which shows that some orders have much higher sales values and increase the average.

## Machine Learning

For sales forecasting, the monthly sales data was used.

Two regression models were tested:

- Linear Regression
- Random Forest Regression

The models were evaluated using RMSE and R² score.

| Model | RMSE | R² |
|---|---:|---:|
| Linear Regression | 23,619.29 | 0.0332 |
| Random Forest Regression | 16,094.10 | 0.5511 |

The Random Forest model performed better than Linear Regression based on the RMSE and R² results.

## Key Findings

Some important findings from the analysis are:

- Technology was the best-performing category with total sales of 827,455.87.
- West was the best-performing region with total sales of 710,219.68.
- Canon imageCLASS 2200 Advanced Copier was the top-selling product with sales of 61,599.82.
- November 2018 had the highest monthly sales of 117,938.15.
- February 2015 had the lowest monthly sales of 4,519.89.

## Recommendations

Based on the analysis, some recommendations are:

- Focus more on Technology products because they have the highest sales.
- Study the reasons for lower sales in the South region and try to improve its performance.
- Keep sufficient stock of products that have high sales.
- Plan promotions and inventory according to high-demand periods.
- Future forecasting can be improved by using more business-related features.

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
