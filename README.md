# Credit Card Spending Analysis

This project analyzes credit card user spending behavior using Python, Pandas, and Matplotlib.  
The goal is to preprocess the data, visualize different breakdowns, and extract meaningful insights.

## Datasets
- users.csv – demographic info (User, Gender, City, Yearly Income, etc.)  
- transactions.csv – transaction details (User, Merchant City, Time, Amount, etc.)

## Data Preparation
- Handled missing values  
- Cleaned Yearly Income - Person (`$` removed → float)  
- Converted Time to datetime and extracted `Hour`  
- Merged datasets on `User`  
- Filtered out `"ONLINE"` merchant city  

## Visualizations
1. Top 10 Cities by Spending – bar chart  
2. Hourly Spending Trend – line chart  
3. Spending by Gender – bar chart  
4. Yearly Income vs Total Spending – scatter plot
5. Spending by Age - scatter plot  

## Key Insights
- Spending peaks at certain hours.  
- One city dominates total spending; others are much lower.  
- Female users spend slightly more than male users.  
- Higher income does not necessarily mean higher spending.
- Age does not strongly influence total spending.  

## Requirements
pandas
matplotlib
numpy

