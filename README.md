# Superstore Data-Demo

## Introduction
The data is  for year 2021 orders from the 3 year dataset (2019-2021) sourced online, which belongs to Superstores. I have opted for this data to  my skill in data cleaning, analysis and visualization.

## Power BI Concept Application

1. DAX: Calculated columns (Average Sales, Order count), Custom columns
2. Data Modelling

## Problem Statement
1.  What is the total number of sales made in year 2021?
2.  What is the average sales figure for year 2021?
3.  What is the profit figure for year 2021?
4.  What is the number of orders in year 2021?

## Data Source
The superstore online dataset was assessed and I decided to generate insight into what the management might be interested in  terms of year to date total sales, profit earned, number of orders etc, for strategic decision making.
- Year 2021 orders with 3313 rows and 21 columns

## Data Cleaning/Transformation
The data was cleaned using the Power BI Power Query editor
- Customns columns were created
- Data types were changed from Text to whole numbers, monetary value columns were assigned $ from default decimal and numeric xters.
- Calculated columns(DAX): of Avg. Sales-sale sum/order count 
- Sum('Store sales'[Sales]) / count('Store sales'[Product ID])

## Data Visualization

|[](Store KPI snapshot.jpg)
---

![Store KPI snapshot](https://github.com/yemilad/Store-Data-Demo/assets/165817613/556e7732-5dd4-48d4-baae-95889d643c2b)

- Year 2021 total sales was $733.2K
- The profit for 2021 was $93.4K
- Average sales was 0.2k
- Number of orders made in year 2021 was 3,300
- The western region in North America has the highest number of sales-$250.1K
- Orders falling in the technology category account for a sales chunk of 37.06%

  ## Conclusion
  



