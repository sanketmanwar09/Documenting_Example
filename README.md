# E-Commerce Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Recommendations](recommendations)
- [References](refernces)

### Project Overview

This data analysis project aims to provide insights into the sales performance of an e-commerce company over the past year. By analyzing various aspects of the sales data , we seek to identify trend , make data -driven recommendations, and gain a deeper understanding of the company's performance.

![filter](https://github.com/sanketmanwar09/Documenting_Example/assets/155233255/80cab5ba-60c9-4911-a82a-062daccd0e3e)


### Data Sources

Sales Data: The primary dataset used for this analysis is the "sales_data.csv" file , containing detailed information about each sale made by the company.

### Tools
- Excel- Data Cleaning 
   - [Download_here](https://microsoft.com)
- SQL Server- Data Analysis
- Power BI- Creating  reports

### Data Cleaning/Preparation

In the initial dat preparation phase , we performed the following tasks:
1. Data loading and inspection
2. Handling missing values
3. Data cleaning and formatting


###Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as :

- What is overall sales trewnd?
- Which products are top sellers?
- What are the peak sales periods?

### Data Analysis

Include some interesting code/features worked with during analysis(subquery,CTE, roundof function)

```sql
SELECT *FROM table1
WHERE cond = 2;
```

###Results/Findings
The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2. Product Category A is the best performing category in terms of sales and revenue.
3. Customer segments with high lifetime value (LIV) should be targeted for marketing efforts.

### Recommendations
Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high-LIV customers effectively.


 ### Limitations 

 I had to remove all zero values from budget and revenue columns because they would have affected the accufracy of my conclusions from analysis, There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue.

 ### References

 1. LInks
 2. books(SQL FOR BUSINESS BY WERTY)
 3. [Stack Overflow](https://stack.com)
