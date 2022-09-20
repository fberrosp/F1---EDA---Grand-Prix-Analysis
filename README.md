# F1-EDA-Grand-Prix-Analysis
Analysis go historic Formula 1 data.

## Problem Statement
* What factors will determine who is more likely to win a GP at that specific GP?
* How did lap times change over time at each GP?
* Is there a relationship between grid starting position and winning a GP?
* Is there a relationship between constructor and GP?
* Is there a relationship between driver and GP over the years?

## Data Cleaning

1. Checking for NA values and visualize them in heatmap.
1.1 Determined why they are missing. Missing Completely At Random (MCAR), Missing At Random (MAR), Missing Not At Random (MNAR).
1.2 In case of not at random, found most common ocurrence (median) and fill the values.
2. Checking data types and format them appropriately.
3. Removed redundant variables. URLs, number, code, etc.
4. Merge data
5. Convert data to numeric, e.g: categorical and date data.

## Data Exploration

1. Deal with outliers. Use reasoning to determine boundaries and parameters.
1.1 Check for outliers in univariate (same variable, outside range) and multivariate analysis (outside range hwne plotted against other variables). 
1.2 Normalized data for univariate analysis.
2. Analize the standard deviation of variables.
3. Plot correlation graph
3.1 List positive and negative correlations.
4. Pair plot to show correlation between relevant variables
5. Box plot
        
#3. ML...
