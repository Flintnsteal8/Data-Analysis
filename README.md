# Data-Analysis
Overview

This project involves analyzing multiple datasets to derive insights about themes, sales, social media activity, Google search data, and manufacturer performance. The key objectives include identifying trends, discovering business opportunities, and visualizing data.

File Structure

Datasets

google_search_data.csv: Contains data on search volumes for various themes.

product_manufacturer_list.csv: Lists products and their manufacturers.

sales_data.csv: Details sales performance data.

social_media_data.csv: Tracks social media activity related to themes.

Theme_list.csv: Lists all themes with their details.

Theme_product_list.csv: Maps themes to products.

Scripts

Main script for data loading, cleaning, analysis, and visualization.

Getting Started

Prerequisites

Python 3.x

Required libraries: pandas, matplotlib, numpy

Google Colab or a similar environment to run the script.

Mounting Google Drive

The datasets are stored on Google Drive. Use the following command to mount your drive:

from google.colab import drive
drive.mount('/content/drive')

Tasks

Task 1: Data Cleaning

Objective: Identify missing and duplicated data in all datasets and calculate their percentages.

Key Steps:

Use .isnull().sum() to identify missing values.

Use .duplicated().sum() to count duplicate records.

Calculate percentages of missing and duplicate data.

Clean the datasets by dropping duplicates and missing values.

Task 2: Analyzing Themes

Number of Themes Present: Count the total number of themes.

Themes in Social Media: Identify themes mentioned and themes with no publicity.

Themes in Google Search: Count the number of themes searched on Google.

Themes Contributing to Sales: Merge datasets to identify themes linked to sales.

Manufacturer A's Themes: Count the number of themes Manufacturer A is involved in.

Task 3: Consumer Preferences

Top 5 Themes (Sales): Identify the top themes based on sales.

Top 5 Themes (Social Media): Identify the top themes based on social media activity.

Top 5 Themes (Google Search): Identify the top themes based on Google search data.

Visualizations: Bar plots to compare the top themes across different sources.

Task 4: Time Series Analysis

Objective: Analyze trends for the theme GMO Free over time.

Methodology:

Filter data for the GMO Free theme.

Group data monthly and visualize trends for sales, social media activity, and Google search data.

Identify correlations between trends.

Task 5: Manufacturer Analysis

Market Share: Calculate the total sales units for each vendor and their percentage distribution.

Top Manufacturers: Identify the top 3 manufacturers by sales.

Visualizations: Pie chart for market share distribution.

Task 6: Business Opportunities

Competitor Analysis: Identify competitors for a specific theme (e.g., GMO Free) against Manufacturer A.

High-Opportunity Themes:

Identify themes with high revenue potential.

Analyze sales trends for the top themes to assess growth potential.

Visualizations: Line plots for sales trends of high-opportunity themes.

Usage

Load datasets using pandas.read_csv().

Perform cleaning to remove missing and duplicate data.

Use the analysis steps provided in each task to generate insights.

Visualize the results with matplotlib.

Key Insights

Trends: The GMO Free theme showed declining trends in late 2019 across all metrics.

Top Themes: High sales, social media activity, and search volumes were concentrated among a few themes.

Manufacturer A: Manufacturer A has significant involvement in themes but faces competition in areas like GMO Free.

Business Growth: Certain themes show steady growth, indicating strong potential for future investments.

Conclusion

This project demonstrates how integrating data from diverse sources can provide actionable insights for theme performance, market trends, and competitive analysis. The findings can guide strategic decisions in marketing and product development.
