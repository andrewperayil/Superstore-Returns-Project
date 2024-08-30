# Superstore-Returns-Project-READ.ME
Please refer to the specific sections for detailed information on each aspect of the project

## Deployment Instructions
Deployment for this Tableau project requires Tableau Server or Tableau Online for hosting. System requirements include a supported web browser for accessing the Tableau dashboard, such as Google Chrome or Mozilla Firefox, and stable internet connectivity. Additionally, the project's compatibility relies on the version of Tableau Desktop used to create it, with the latest recommended for optimal performance.


## Link to Project 
* https://public.tableau.com/views/Sprint5Project_17214203465910/WhatsCausingReturns?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
  
## Table of Contents
### Introduction
#### Part 1: What is Causing Returns?
* Correlation Analysis
* Return Rate by Product Category
* Return Rate by Customer
* Geographic Analysis
* Seasonal Effect Analysis
* Composite Charts
#### Part 2: Presenting Your Analysis and Dashboard
* Story Arc Construction
#### Part 3: Conclusion and Proposed Next Steps

----------------------------------
### Introduction
The aim of this project was to analyze the high number of returned orders at the Superstore. Prepared an analysis for the CEO to understand the causes of returns and suggested strategies to reduce them.

#### Part 1: What is Causing Returns?
* Correlation Analysis
  * Scatterplot showing the correlation between total sales and total returns, aggregated by product subcategory.
  * ![image](https://github.com/user-attachments/assets/dab2fcab-8269-4640-9309-56938dffdbbb)

  <img width="1437" alt="Screen Shot 2024-02-20 at 1 47 03 PM" src="https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/a5399b6c-89e5-446f-9171-e56404fa9fa5">
* Return Rate by Product Category
  * Bar chart displaying the return rate by product category.
  <img width="993" alt="Screen Shot 2024-02-20 at 1 48 00 PM" src="https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/62e2ce82-c5c9-483e-b6a4-7c32923a625d">
  <img width="904" alt="Screen Shot 2024-02-20 at 1 49 01 PM" src="https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/42958146-b9a2-4b0e-a302-c5c6b8d305d1">
* Return Rate by Customer
  * Analysis of return rate by customer, filtering out customers with only 1 order.
* Geographic Analysis
  * Map representation of the return rate by geographic measure (state, city, etc.).
  <img width="857" alt="Screen Shot 2024-02-20 at 1 50 34 PM" src="https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/90c57355-9278-42b1-819d-fbc2e6b73de3">
* Seasonal Effect Analysis
  * Analysis of return rate by time measure (month, week, etc.) to detect seasonal effects.
  <img width="888" alt="Screen Shot 2024-02-20 at 1 51 26 PM" src="https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/ba92cf82-d49b-4deb-92ff-a67082910f96">
* Composite Charts
  * Two composite charts showing the return rate based on multiple factors (date, geography, product category, etc.).
  * <img width="807" alt="Screen Shot 2024-02-20 at 1 52 19 PM" src="https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/a6106037-cfb0-44ba-9f87-7b14a3f7dec4">
#### Part 2: Presenting Your Analysis and Dashboard
* Story Arc Construction
  * Drafting the story arc using captions for each Story Point, including:
    * Summary of returns analysis
      * Returns can be measured in 3 ways, however the most optimal way is by the Average Return Rate, vs's the Total # of Returns or Total Cost of Returns. When looking at the returns 
        rate, it directly reflects the percentage of customers who are not satisfied with the product, whereas the total number and cost of returns focus more on the financial impact 
        and operational purposes respectively, which for this exercise we are focusing on root cause of the returns. The Key root causes of returns are customers who are unsatisifed 
        with technology products across all regions with an average return rate of 0.273 from 2018-2021
      * And West Coast Customers with an average return rate of 0.4 across all categorys of items from 2018-2021; office supplies having the highest out of the 3 category's of 4.29
    * Measurement of returns
    * Identification of key root causes
    * Overview of each dashboard component
    * Demonstration of dashboard usage
    <img width="1061" alt="Screen Shot 2024-02-20 at 1 53 54 PM" src="https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/ad2994ca-4876-44ac-a311-29f67f7646f1">
#### Part 3: Conclusion & Proposed Next Steps
* The average highest return rates stem from Technology products within the West Coast region over the period from 2018-2021. We also see very low sales across office supplies within the same period
* Based on the data, the business should do away with all products in the western region, mainly technology products
* Office supplies generate very low sales within 2018-2021 and should also be reviewed for removal
* Implement the Dashboard to all relevant stakeholders
* Follow directions in the Explanation of Visuals portion of the dashboard
* Use filters to narrow down and identify root causes of returns
