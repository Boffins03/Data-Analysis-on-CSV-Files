# Task 5: Data Analysis on CSV Files

## Objective
Analyze sales data from a CSV file using Python and Pandas to gain basic insights and visualize trends.

## Tools Used
- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook

## Files Included
- `sales_analysis.ipynb` – Jupyter Notebook containing the analysis code.
- `sales_data.csv` – Sample CSV dataset with sales records.
- Output charts (generated within the notebook).

## Steps Performed
1. **Load CSV Data**
   - Used `pandas.read_csv()` to load the sales dataset.

2. **Explore the Dataset**
   - Displayed first few rows (`.head()`).
   - Checked column types and structure (`.info()`).
   - Generated basic descriptive statistics (`.describe()`).

3. **Data Aggregation**
   - Grouped sales by `Product` and calculated total sales.
   - Grouped sales by `Month` (extracted from `Date`) and calculated monthly totals.

4. **Data Visualization**
   - Created bar charts for:
     - Sales by Product
     - Sales by Month
