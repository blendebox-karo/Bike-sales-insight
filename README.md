# Bike-sales-insight
Bike Sales Customer Insight and Visualization

## Project Details
The goal is to identify the ideal customer for a bike shop. To accomplish this, we will analyze customer data from an Excel sheet containing various information on Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, and Purchased Bike.

## Setup
To start the project, data cleaning was performed to ensure accurate analysis. This included the removal of duplicate entries in the dataset, adding an extra column for customer age brackets for better visualization. Furthermore, the data was updated to be more interpretable, such as replacing "m" and "f" with "male" and "female", and "m" and "s" with "married" and "single". Additionally, I ensured there was no missing data and that each field had the correct data type.

<img width="960" alt="cleaned-bike-data" src="https://github.com/user-attachments/assets/1f700e96-c2ba-43ac-8ee2-0dbdee59a27d">

These steps were essential to ensure that the data was properly formatted for analysis and would yield accurate results. We initally started with 1026 records and now we have 1000.

## Analysis
Now that we have clean data, we can perform exploratory data analysis to gain insights and patterns in the data.

### Basic Questions:
What is the age bracket of customers who purchase bikes from the shop?
What is the gender of customers who purchase bikes from the shop?
What is the income range of customers who purchase bikes from the shop?
What is the most common occupation of customers who purchase bikes from the shop?
What is the most common region of customers who purchase bikes from the shop?
What is the most common commute distance of customers who purchase bikes from the shop?
Does the marital status of customers have any correlation with the likelihood of purchasing a bike from the shop?

By answering these questions, the bike shop can develop a better understanding of their ideal customer and tailor their marketing strategies to attract more of these customers.

## Data Exploration
We will start by segmenting the customers based on their age brackets, gender, income, marital status, etc.

I used the customer data to create pivot tables that grouped the customers based on different criteria. Using these groups, I created charts that show key insights. Additionally, differnt functions were used to perform calculations.

<img width="960" alt="data exploration using pivot tables" src="https://github.com/user-attachments/assets/8eeea1cb-ec9d-41b6-98fd-6c5738d87918">


To make it easy to view all this information at once, I created a dashboard that displays all the charts. I also added a slicer to the dashboard, which allows users to filter the data based on different criteria. This makes it easy to identify the customer segments that are most likely to purchase a bike.

<img width="435" alt="visualization dashboard" src="https://github.com/user-attachments/assets/b05f7647-4f24-4234-b284-03fc58860324">

## Key Findings
Using the dashboard, we were able to determine the following insights:

Age group: The largest group of bike purchasers falls within the middle age range of 31-50.
Education level: The majority of customers who purchase bikes have completed partial high school education.
Occupation: The most prevalent occupation among bike purchasers is in management.
Region: North America is the region where most bike purchases are made.
Commute distance: Most bike purchasers have a commute distance of 0-1 mile.
Marital status: Married customers are more likely to purchase a bike, possibly due to their combined income being greater than that of a single income household.

## Recommendations

Based on these findings, the business can implement the following actionable steps to improve sales:

Target marketing efforts towards the middle age range of 31-50, which is the largest group of bike purchasers. This can be done through targeted advertisements, promotions, and events.
Cater to the needs and interests of customers in management positions, who are the most prevalent occupation among bike purchasers. This can be done by offering high-end, performance-focused bikes and accessories.
Focus sales efforts on North America, which is the region where most bike purchases are made. This can involve increasing inventory and offering promotions specific to this region.
Cater to married customers by offering high-end, performance-focused bikes and accessories. Additionally, consider offering promotions for couples who purchase bikes together.

In conclusion, these findings provide valuable insights into the demographics and preferences of bike purchasers. By implementing these actionable steps, the business can improve sales and better cater to the needs and interests of its target market.
