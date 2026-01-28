# Sales_Analysis

## Table Of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview

This data analysis project examines online retail transaction data of a retailed industry across different countries, spanning between the years of 2003 to 2005 to uncover key insights into sales trends, customer behavior, and product demand.By analyzing this dataset, businesses can gain insights into key sales performance indicators, improve inventory management, optimize marketing strategies, and enhance sales forecasting for better decision-making.

### Data Sources

sales data: The primary dataset used for this analysis is the "Sales_data_sample.csv", containing detailed sales information made in the retailed industry

### Tools

- Jupyter Notebook - Open source for writing of codes [Download here](https://jupyter.org)
- Python - Data Analysis
- PowerBI - Creating Reports

### Data Cleaning/Preparation

in the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as;
- How have sales evolved annually?
- Which months generate the highest sales volume?
- Which countries contribute the most revenue?
- What types of products do customers order the most?
- What are the top 5 best-selling products based on total revenue?

### Data Analysis

include some codes/features worked with

```python
df.isnull().sum()

df.columns = df.columns.str.lower()
```

### Results/Findings

The analysis results are summarized as follows;
1. The highest amount of sales was made in the year 2024, followed by the year 2003 then the year 2005 made the lowest amount of sales.
2. The month of november experienced the highest amount of sales while the month of june experienced the lowest amount of sales.
3. USA contributed the most revenue while ireland contributed the least revenue.
4. The most ordered products are classic cars whiile the least ordered products are trains.
5. The top 5 best selling products are;
    - Classic cars,
    - Vintage cars,
    - Motorcycles,
    - Planes,
    - Trucks and Buses.

### Recommendations

Based on the analysis, we recommend the following actions;
1. Leverage Peak Sales Periods: Since November records the highest sales, increase marketing campaigns, promotions, and inventory levels ahead of this month to maximize revenue.
2. Improve Low-Performing Periods: Sales are lowest in June, so targeted discounts, bundle offers, or special promotions can be introduced to stimulate demand during this period.
3. Focus on High-Revenue Markets: With the USA contributing the most revenue, the company should prioritize this market through personalized marketing, faster delivery options, and localized promotions, while exploring growth opportunities in underperforming regions like Ireland.
4. Optimize Product Strategy: Since classic cars and vintage cars are the most ordered products, the business should ensure consistent availability, consider expanding related product lines, and feature them prominently in marketing efforts.
5. Reevaluate Low-Demand Products: Products like trains, which show low demand, should be reviewed for potential improvement, repositioning, or discontinuation to reduce holding and operational costs.

### Limitations

I had to remove some columns with many missing values because they will affect the accuracy of my results.

### References

1. Google [link](https://www.google.com)
2. python for data analysis by Wes McKinney
