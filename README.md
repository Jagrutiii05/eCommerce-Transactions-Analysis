# eCommerce Transactions Dataset Analysis

This repository contains the code and reports for analyzing an eCommerce Transactions dataset. The goal is to perform Exploratory Data Analysis (EDA), build a Lookalike Model, and conduct Customer Segmentation/Clustering. The analysis is based on three datasets: Customers.csv, Products.csv, and Transactions.csv.

## Files
1. **Customers.csv**: Customer data, including unique IDs, names, regions, and signup dates.
2. **Products.csv**: Product information, including IDs, names, categories, and prices.
3. **Transactions.csv**: Transaction records, detailing the transactions between customers and products.

### 1: Exploratory Data Analysis (EDA) and Business Insights
- Performed EDA on the dataset.
- Derived actionable business insights based on the analysis.
- Results in a Jupyter Notebook and a PDF report.

### 2: Lookalike Model
- Built a model to recommend 3 similar customers based on profile and transaction history.
- A CSV file containing the top 3 lookalikes for each customer (CustomerID: C0001 - C0020).

### 3: Customer Segmentation / Clustering
- Applied clustering techniques using customer and transaction data.
- Calculated DB Index and other metrics for evaluating clustering quality.
- Visualized the clusters with appropriate plots.

## Files in the Repository
- **Jagruti_Piprade_EDA.pdf**: PDF report of the EDA and business insights.
- **Jagruti_Piprade_EDA.ipynb**: Jupyter notebook with the EDA code.
- **Jagruti_Piprade_Lookalike.csv**: CSV file with lookalike recommendations.
- **Jagruti_Piprade_Lookalike.ipynb**: Jupyter notebook for the lookalike model development.
- **Jagruti_Piprade_Clustering.pdf**: PDF report on clustering results.
- **Jagruti_Piprade_Clustering.ipynb**: Jupyter notebook for clustering code.

## How to Run
- Install necessary Python libraries (e.g., pandas, scikit-learn, matplotlib, seaborn).
- Run the Jupyter notebooks in sequence for full analysis.
