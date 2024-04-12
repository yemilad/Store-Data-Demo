# Superstore Performance Review
![](Superstore_Office.jpg)


![Superstore_Office](https://github.com/yemilad/Store-Data-Demo/assets/165817613/8578aebf-ffd3-4baa-9ddc-7d9696daffa4)
---


## Introduction
The data is  for year 2021 orders from the 3 year dataset (2019-2021) sourced online, which belongs to Superstores. I have opted for this data to display  my skill in data cleaning, analysis and visualization.

**_Disclaimer_** : The datasets used are fictional and do not depict any real company, institution, or country. They are solely for demonstration purposes to showcase the capabilities of Power BI.

## Power BI Concept Application
- Data Analysis Expression (DAX): Calculated columns (Average Sales, Order count) and Custom columns


## Problem Statement
1.  What is the total number of sales made in year 2021?
2.  What is the average sales figure for year 2021?
3.  What is the profit figure for year 2021?
4.  What is the number of orders in year 2021?

## Data Source
The superstore online dataset was assessed and I decided to generate insight into what the management might be interested in  terms of year to date total sales, profit earned, number of orders etc, for strategic decision making.
- Year 2021 orders with 3313 rows and 21 columns

## Data Cleaning & Transformation
The data was cleaned using the Power BI Power Query editor
- Customns columns were created
- Data types were changed from Text to whole numbers, monetary value columns were assigned $ from default decimal and numeric xters.
- Calculated columns(DAX): of Avg. Sales-sale sum/order count 
- Sum('Store sales'[Sales]) / count('Store sales'[Product ID])

## Data Visualization


![Store KPI snapshot](https://github.com/yemilad/Store-Data-Demo/assets/165817613/556e7732-5dd4-48d4-baae-95889d643c2b)
---
- Year 2021 total sales was $733.2K
- The profit for 2021 was $93.4K
- Average sales was $0.2k
- Number of orders made in year 2021 was 3,300
- The western region in North America has the highest number of sales-$250.1K
- Orders falling in the technology category account for a sales chunk of 37.06%

    ## Conclusion & Recommendation
  From the foregoing, it can be seen that there are other regions whose sales metrics need to improve. Hence, it is recommended that management should focus on;
1. Focus on Increasing Average Order Value: Implement strategies such as bundling products, upselling, or offering discounts for bulk purchases to increase the average sales per order.

2. Explore Market Expansion: While the Western region is performing well, consider exploring opportunities in other regions to diversify and expand sales channels.

3. Enhance Technology Product Offerings: Given the significant contribution of technology category orders, continue to innovate and improve offerings in this segment to maintain or increase market share.

4. Cost Management: Despite a good profit margin, continue to monitor and optimize costs to ensure profitability remains sustainable.

5. Customer Segmentation and Targeting: Analyze customer data to identify high-value segments and tailor marketing strategies to effectively target and attract these customers.

6. Continuous Performance Monitoring: Regularly track sales, profit margins, and other key metrics to identify trends, challenges, and opportunities for improvement throughout the year.
  
  



