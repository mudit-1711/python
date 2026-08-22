# Automated Exploratory Data Analysis (EDA) with Profiling

This directory showcases the use of automated data profiling libraries to generate comprehensive, interactive, and high-fidelity HTML reports from tabular datasets.

## Contents

*   **[`practice.ipynb`](file:///d:/python/ydata-profiling/practice.ipynb)**: A Jupyter notebook that reads source CSV files and uses a profiling engine to generate HTML reports.
*   **Generated HTML Profile Reports**:
    *   **[`doremon_gadgets.html`](file:///d:/python/ydata-profiling/doremon_gadgets.html)**: Interactive profile of the Doraemon gadget library dataset (types, descriptions, usage).
    *   **[`ipl.html`](file:///d:/python/ydata-profiling/ipl.html)**: Extensive report containing statistics, trends, and variables of Indian Premier League (IPL) matches.
    *   **[`netflix.html`](file:///d:/python/ydata-profiling/netflix.html)**: Automated analysis of Netflix title catalog data.

## Key Features of Generated Reports

Automated profiling reports generate comprehensive views for any dataset in a single click:
1.  **Overview**: Key dataset metrics (number of variables, missing values, duplicates, size).
2.  **Variable-level Statistics**: Mean, median, minimum, maximum, cardinality, and type detection.
3.  **Correlations**: Heatmaps demonstrating Spearman, Pearson, and Kendall correlation matrices.
4.  **Missing Values**: Visual representation of missing data density (matrix, bar chart, heatmaps).
5.  **Warnings**: Auto-detected issues like high cardinality, imbalance, high correlation, or constant values.

## How to Run & Generate Reports

Ensure you have the profiling package installed:
```bash
pip install pandas ydata-profiling
```

Execute the commands inside **[`practice.ipynb`](file:///d:/python/ydata-profiling/practice.ipynb)** to read datasets and call:
```python
from ydata_profiling import ProfileReport

profile = ProfileReport(dataframe, title="Data Report")
profile.to_file("output.html")
```
