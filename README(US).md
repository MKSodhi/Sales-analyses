# Sales-Analyses

## Project Description: Data Treatment and Analysis

### Overview:
This project focuses on the analysis of sales data from a fictional electronics store. The goal is to gain insights into various aspects of the business by exploring and visualizing the data. The analyses performed include identifying the best month for sales, determining the most profitable cities, optimal times for advertising, frequently sold product combinations, and the top-selling products.

### Data Cleaning and Preprocessing:
The dataset used for this analysis was collected across multiple months. Before conducting any analysis, the data underwent a thorough cleaning process, including:
- Merging monthly sales data into a single dataset.
- Converting data types to their appropriate formats.
- Handling missing values and removing any inconsistencies.
- Extracting additional information, such as the city from the purchase address and the hour from the order date, to facilitate more granular analyses.

### Business Questions Addressed:
The analysis aimed to answer the following key business questions:
1. **What was the best month for sales?** How much revenue was generated during that month?
2. **Which city sold the most products?** What are the contributing factors to this trend?
3. **What time should advertisements be displayed** to maximize the likelihood of customer purchases?
4. **What products are most often sold together?** Understanding these combinations can help optimize cross-selling strategies.
5. **What product was sold the most?** Why did it outperform others?

### Methods and Techniques:
Some of the methods and techniques used to answer these questions include:
- Grouping and aggregating data to summarize sales by month, city, and hour.
- Visualizing data with bar plots and line plots to highlight trends and patterns.
- Using combinations and frequency analysis to discover frequently sold product pairs.
- Applying various Python libraries, such as `pandas` for data manipulation, `seaborn` and `matplotlib` for data visualization, and `itertools` for combinatorial analysis.
