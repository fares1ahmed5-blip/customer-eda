# Customer Data: Exploratory Data Analysis

A Jupyter notebook exploring a customer dataset (age, acquisition cost, gender, segment, country, region).

## What it does
- Loads and inspects the data
- Distributions of customer age and acquisition cost
- Customers by gender and by segment
- Data quality checks (unique IDs, duplicate rows)
- Country summary (customer count, average age, average acquisition cost)
- Gender mix per segment, and a region x segment heatmap of average acquisition cost

## Tools
Python, pandas, NumPy, matplotlib, seaborn, Jupyter.

## How to run
1. `pip install pandas numpy matplotlib seaborn jupyter`
2. Get the dataset as `customer_master.csv` and change the path in the third cell.
3. `jupyter notebook customer_eda.ipynb`

## Note
The CSV is not included in this repo (the original path was on a local machine). The notebook keeps its saved outputs, so the tables and charts are visible on GitHub without running it.
