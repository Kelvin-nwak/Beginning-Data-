# Data Analysis on Computech and Microworld Stores

## Table of Content
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparations](data-cleaning/preparations)


## Project Overview

This project aims to conduct a comprehensive data analysis of two retail stores, Computech and Microworld. The objective is to compare their sales performance and other relevant metrics to derive insights and actionable recommendations. This analysis will help identify strengths and weaknesses, uncover trends, and support strategic decision-making for both stores.

![Screenshot 2024-04-25 134028](https://github.com/Kelvin-nwak/Beginning-Data-/assets/167860887/f75b23c9-aeda-4eb6-a3f3-099007875998)



### Data Sources

Sales Data: The primary datasets used for this analysis is the "sales_data.cv" file, containing detailed information about each sale made by the company.

### Tool

- Excel - Data Cleaning
   - [Download here](https://www.microsoft.com/en-ng)
- Power Bi - Creating Reports


  ### Data Cleaning/Preparations

  in the initial data preparation phase, we performed the following tasks:
  1. Data loading and inspection.
  2. Handling missing values.
  3. Data cleaning and formatting.
 
### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- what is the overall sales by store?
-  what are the overall sales by manager?
-  what are the overall sales by month?
-  what are the overall sales by category?

### Data Analysis

Include some interesting Code/features worked with

```sql
SELECT * FROM table1
WHERE cond = 2;
```

### Result/Findings

The analysis results are summarized as follows:
1. The company's sales have been steadily increasing 📈 over the past year, with a noticeable peak during the holiday season.
2. Memory cards are the best-performing category in terms of sales and revenue.
3. Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

### Recomendation

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high-LTV customers effectively.

  ### Limitation

I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue.

### References

1. SQL for businesses by werty.
2. [Stack Overflow](https://stackoverflow.com/)
     

  
