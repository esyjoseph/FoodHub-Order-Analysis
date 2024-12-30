# FoodHub-Order-Analysis
A **personal data exploration project** focusing on FoodHub’s order data. This analysis aims to uncover trends in restaurant demand, cost patterns, and delivery performance, offering actionable insights to enhance overall operations and customer satisfaction.

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Dataset Description](#dataset-description)  
3. [Objectives](#objectives)  
4. [Technologies Used](#technologies-used)  
5. [Key Findings](#key-findings)  
6. [Recommendations](#recommendations)  
7. [License](#license)

---

## Project Overview

With the surge in online food delivery services, **FoodHub** manages orders from multiple restaurants while coordinating drivers and order status updates. This repository presents a comprehensive exploration of `foodhub_order.csv` data. By investigating restaurant popularity, cost distributions, preparation/delivery times, and customer ratings, we derive meaningful insights and best practices to improve FoodHub’s business operations.

---

## Dataset Description

- **File Name**: `foodhub_order.csv`  
- **Number of Rows**: 1,898  
- **Number of Columns**: 9  

**Data Dictionary**  
1. **order_id**: Unique identifier for each order  
2. **customer_id**: Unique ID of the customer  
3. **restaurant_name**: Name of the restaurant fulfilling the order  
4. **cuisine_type**: Type of cuisine (e.g., American, Italian, Japanese)  
5. **cost_of_the_order**: Monetary value of the order  
6. **day_of_the_week**: Whether the order was placed on a weekday or weekend  
7. **rating**: 1–5 star rating (or “Not given” if unrated)  
8. **food_preparation_time**: Time (minutes) from restaurant confirmation to driver pickup  
9. **delivery_time**: Time (minutes) from driver pickup to drop-off at the customer location  

---

## Objectives

1. **Assess Restaurant Popularity**  
   Identify which restaurants dominate demand and which cuisines thrive on weekdays vs. weekends.  

2. **Examine Cost Patterns & Revenue**  
   Investigate typical order cost ranges, high-value purchases, and how commission rates impact revenue.  

3. **Analyze Operational Efficiency**  
   Evaluate preparation times, delivery windows, and identify potential bottlenecks, especially on weekdays vs. weekends.  

4. **Explore Customer Ratings**  
   Determine how missing ratings affect data quality and whether longer delivery times correlate with lower feedback.

5. **Propose Actionable Recommendations**  
   Based on findings, suggest strategic steps for FoodHub to enhance user satisfaction and streamline operations.

---

## Technologies Used

- **Python**: Primary language  
- **pandas**: Data cleaning and manipulation  
- **NumPy**: Numerical computations  
- **matplotlib** & **seaborn**: Data visualization  
- **Jupyter Notebook**: Analysis environment

---

## Key Findings

1. **Top Restaurants & Cuisines**  
   - A handful of restaurants (e.g., Shake Shack, The Meatball Shop) receive the bulk of orders, showcasing brand loyalty.  
   - American cuisine dominates on weekends, while other types (Japanese, Italian) maintain consistent demand.

2. **Cost Analysis**  
   - Most orders cost between \$7 and \$17. Approximately 29% exceed \$20, contributing significantly more to FoodHub’s commission revenue.  

3. **Delivery & Prep Times**  
   - Mean delivery time is ~24 minutes, but it’s notably slower on weekdays (28 minutes) than weekends (22 minutes).  
   - About 10.5% of orders take over an hour from order placement to delivery, warranting further optimization.

4. **Missing Ratings**  
   - Nearly 39% of orders are unrated, limiting full insight into customer satisfaction. Longer delivery times show a slight correlation with lower ratings.

---

## Recommendations

1. **Incentivize Feedback**  
   - Introduce loyalty points or discounts for completed ratings to reduce the 39% unrated gap and better measure restaurant performance.

2. **Optimize Delivery Operations**  
   - Focus on weekday traffic patterns (e.g., route planning, driver scheduling) to reduce average delivery times during work hours.  
   - Explore micro-fulfillment strategies or partner with more restaurants close to busy customer clusters.

3. **Promote Popular & Underserved Cuisines**  
   - Collaborate with top-rated American and Japanese restaurants for cross-promotions.  
   - Onboard underserved but emerging cuisines if data suggests potential growth.

4. **Price & Revenue Strategy**  
   - Highlight recommended price points (\$7–\$17) to cater to the majority of customers.  
   - Emphasize upselling combos or premium deals for those willing to spend over \$20, where FoodHub captures a higher commission.


## License

This project is for **educational and illustrative purposes**. You’re free to use the code and insights.

---

**Thank You for Exploring the FoodHub Order Analysis!**  
Feel free to reach out with any suggestions, questions, or feedback.
theestherjoseph@gmail.com
