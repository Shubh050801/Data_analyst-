
# Exploratory Data Analysis (EDA) on Supermarket Sales https://github.com/Shubh050801/Supermarket_Sales_EDA/blob/main/EDA%2023.pdf

This project provides a thorough Exploratory Data Analysis (EDA) of a supermarket sales dataset to derive insights that can drive business decisions and strategies. The dataset captures key details of customer purchases across various branches, including demographics, product lines, and payment methods. This analysis seeks to understand customer behavior, sales trends, and performance metrics across different dimensions.

 Key Features of the Project:
- Data Cleaning and Preparation:
  - Handling missing values and replacing them with meaningful estimates using methods like mean and mode imputation.
  - Identifying and removing duplicate entries to ensure data quality.
  - Converting date and time columns into appropriate formats for temporal analysis.
  
- Univariate Analysis:
  - Detailed exploration of individual features such as customer ratings, gross income, unit price, and product categories.
  - Identification of trends and patterns through visualizations (histograms, box plots, and distribution plots).
  - Skewness and central tendency analysis for understanding the nature of numeric variables like income and ratings.

- Bivariate and Multivariate Analysis:
  - Investigating relationships between multiple variables, such as the impact of customer ratings on gross income, or sales differences between customer types (members vs. non-members).
  - Using scatter plots, regression plots, and correlation matrices to identify associations between variables.
  - Box plots to compare gross income and other metrics across different categories like product lines, customer type, and payment methods.

- Sales Performance by Branch and Product Line:
  - Analyzing total sales and customer ratings by different branches (Yangon, Mandalay, Naypyitaw).
  - Comparing sales performance across various product lines such as "Health and Beauty," "Electronic Accessories," and "Fashion Accessories."
  - Aggregating sales data to explore differences in revenue generation by branch and product category.

- Correlation and Trend Analysis:
  - Using correlation analysis to identify significant relationships between key numerical features like gross income, unit price, quantity, and customer ratings.
  - Time-series analysis to explore trends in sales and gross income over time using line plots.
  - Pair plots and heatmaps to visualize correlations and patterns in the dataset.

- Customer Behavior Insights:
  - Understanding customer preferences by examining purchasing behavior based on payment method (Cash, Credit Card, E-wallet).
  - Exploring the distribution of customer types (Members vs. Normal) and their contribution to overall sales.

Tools and Libraries Used:
- Pandas: For data manipulation, cleaning, and analysis.
- NumPy: For numerical computations.
- Matplotlib and Seaborn: For creating visualizations, including histograms, scatter plots, and heatmaps.
- Ydata Profiling: For generating a comprehensive profiling report of the dataset.
  
Visual Insights:
- Detailed visualizations are created to make sense of the data, including:
  - Histograms and KDE (Kernel Density Estimation) plots for exploring the distribution of variables like customer ratings and gross income.
  - Correlation heatmaps to identify relationships between numerical features.
  - Box plots and scatter plots for visualizing relationships between variables like branch performance, product line sales, and gender-based purchasing patterns.

Project Structure:
1. Data Loading and Cleaning: Importing the dataset, handling missing values, converting data types, and removing duplicates.
2. Exploratory Data Analysis:
   - Univariate analysis of individual features.
   - Bivariate and multivariate analysis for understanding interactions between variables.
3. Visualization: Creating a variety of plots to visually explore the dataset.
4. Sales Insights: Extracting meaningful insights around sales patterns and customer behavior.
5. Correlation Analysis: Investigating how different numerical features are related.
6. Trend Analysis: Examining sales and gross income trends over time.


This version adds more detail on each step of the process and provides a comprehensive overview of the project's scope. Let me know if you’d like any specific part expanded or adjusted!
