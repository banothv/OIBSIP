# EDA on Retail Sales Data

**Oasis Infobyte SIP — Data Analytics | Level 1 | Task 1**

## Objective
Explore retail sales data to identify sales trends, customer behaviour, product performance, correlations, and actionable recommendations.

## Files
- `EDA_Retail_Sales.ipynb` — complete analysis notebook
- `retail_sales_dataset.csv` — synthetic practice data so the notebook runs immediately

## Important before internship submission
The included CSV is synthetic practice data, **not a Kaggle dataset and not real company data**. The task brief asks interns to source a retail dataset from Kaggle (search `Retail Sales Dataset`, `Superstore Sales`, or `e-commerce sales dataset`). Download the selected dataset, save it in this folder, and replace/rename it to `retail_sales_dataset.csv`. If its columns differ, update the column names in the notebook.

## Run
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook EDA_Retail_Sales.ipynb
```
Run all cells from top to bottom.

## Required internship folder
`OIBSIP/DataAnalytics-L1-EDARetailSales/`

## Checklist
- Initial inspection: shape, dtypes, missing values, duplicates
- Numerical descriptive statistics: mean, median, mode, standard deviation
- Monthly and quarterly sales trends
- Age group and gender analysis
- Top 10 products and category revenue
- Numerical correlation heatmap
- Additional weekday/category revenue heatmap
- Observations and three business recommendations
