# F1-EDA-Grand-Prix-Analysis
Analysis of historic Formula 1 data.

## Problem Statement
* What factors will determine who is more likely to win a GP at that specific GP?
* How did lap times change over time at each GP?
* Is there a relationship between grid starting position and winning a GP?
* Is there a relationship between constructor and GP?
* Is there a relationship between driver and GP over the years?

## Data Cleaning

1. Checking for NA values and visualize them in heatmap.
2. Determined why they are missing. Missing Completely At Random (MCAR), Missing At Random (MAR), Missing Not At Random (MNAR).
3. In case of not at random, found most common ocurrence (median) and fill the values.
4. Checking data types and format them appropriately.
5. Removed redundant variables. URLs, number, code, etc.
6. Merge data
7. Convert data to numeric, e.g: categorical and date data.

## Data Exploration

1. Deal with outliers. Use reasoning to determine boundaries and parameters.
2. Check for outliers in univariate (same variable, outside range) and multivariate analysis (outside range when plotted against other variables). 
3. Normalized data for univariate analysis.
4. Analize the standard deviation of variables.
5. Plot correlation graph
6. List positive and negative correlations.
7. Pair plot to show correlation between relevant variables
8. Box plot
        
## ML...
