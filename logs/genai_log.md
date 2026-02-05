User Prompt 1:

would it be better to have a pytohn program or jupter notebook for this project:

What Your System Must Produce
When run on a dataset, your system must generate a concise EDA output (not just code) that includes:

Dataset Overview

Rows/columns, column names, inferred types, missing-value summary
Basic data quality checks (duplicates, columns with one value, high-missing columns)
Descriptive Statistics

For at least one categorical column: frequency counts + percentages
For at least two numeric columns (if available): min/max/mean/median/mode + dispersion (std, IQR) + outlier flagging (1.5×IQR rule)
Visualizations

At least 5 plots total (e.g., histogram, boxplot, bar chart, scatterplot, correlation heatmap)
Each plot must have a title and labeled axes
Insights (Human-Readable)

5–10 bullet insights that summarize key patterns, anomalies, and what the dataset suggests
A short note on limitations or potential bias (missingness, sampling, coverage, etc.)

AI Response (Summary):
ChatGPT explained the tradeoffs between using a Python script and a Jupyter notebook, recommending a Jupyter notebook for this assignment due to its suitability for exploratory data analysis, inline outputs, visualizations, and narrative explanations. A hybrid approach (logic in .py files, presentation in a notebook) was also suggested.

USER ACTION:

We decided to go with a Jupyter Notebook rather than a Python program for our assignment.

User Prompt 2:

How can I compute summary statistics for numeric columns in a dataset using Python?

Response (Summary):
ChatGPT explained how to compute summary statistics using pandas and how to apply the 1.5×IQR rule to flag potential outliers. It also provided syntax for using Pandas functions to compute summary statistics.

USER ACTION:

We used the suggested pandas functions to display stati