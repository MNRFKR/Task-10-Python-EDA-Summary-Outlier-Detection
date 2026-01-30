# Task-10-Python-EDA-Summary-Outlier-Detection
Step 1
I got a students dataset from Kaggle and imported it into Jupyter. Then I verified the data by checking .shape, .info(), and .head() to confirm rows, columns, and sample records.
Step 2
I generated descriptive statistics using .describe(). This gave me insights into mean, standard deviation, and quartiles for all numeric columns.
Step 3
I calculated missing value percentages for each column. This helped identify which features had incomplete data and needed cleaning.
Step 4
I plotted histograms and boxplots for numeric columns. Histograms showed distributions, while boxplots highlighted potential outliers.
Step 5
I applied the IQR method to detect outliers. This flagged values lying outside the acceptable range for each numeric column.
Step 6
I created an outlier_flag column. This marked each row as True if it contained any outlier, making it easy to filter later.
Step 7
I handled outliers by either removing rows or capping values at IQR bounds. Removing ensures clean data, while capping preserves all rows by limiting extremes.
Step 8
I built a correlation matrix and visualized it with a heatmap. Strong correlations appeared among grade columns (G1, G2, G3), showing clear predictors of final performance
