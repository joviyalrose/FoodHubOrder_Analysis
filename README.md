# FoodHub Order Analysis – Data Science Project

## Project Overview
This project analyzes order data from *FoodHub*, an online food delivery aggregator operating in New York. The objective is to derive actionable insights from customer orders, restaurant demand, delivery performance, and customer ratings to help improve business decisions and customer experience.

This project was completed as part of **Project Foundations for Data Science** and demonstrates end-to-end exploratory data analysis (EDA) using real-world data.

---

## Business Context
With the growing number of restaurants and increasing dependence on online food delivery by students and working professionals, FoodHub aims to:
- Understand demand patterns across restaurants and cuisines
- Improve delivery efficiency
- Enhance customer satisfaction
- Optimize revenue generation strategies

---

## Objective
Analyze historical order data to answer key business questions related to:
- Restaurant popularity
- Cuisine demand
- Delivery and preparation times
- Customer ratings
- Revenue contribution
- Customer behavior

---

## Dataset Description
Each row in the dataset represents a food order placed by a customer.

### Data Dictionary
- **order_id**: Unique order identifier  
- **customer_id**: Customer identifier  
- **restaurant_name**: Name of the restaurant  
- **cuisine_type**: Cuisine ordered  
- **cost_of_the_order**: Order cost in dollars  
- **day_of_the_week**: Weekday or Weekend  
- **rating**: Customer rating (out of 5)  
- **food_preparation_time**: Preparation time (minutes)  
- **delivery_time**: Delivery time (minutes)  

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Performed

### Data Understanding & Cleaning
- Verified dataset shape (1898 rows × 9 columns)
- Checked data types and structure
- Confirmed no missing values
- Converted ratings to numeric format for analysis

---

### Exploratory Data Analysis (EDA)

#### Univariate Analysis
- Distribution of order costs, preparation times, and delivery times
- Frequency of orders by restaurant, cuisine type, and day of week

#### Key Insights
- **Top 5 Restaurants by Orders**:
  - Shake Shack
  - The Meatball Shop
  - Blue Ribbon Sushi
  - Blue Ribbon Fried Chicken
  - Parm

- **Most Popular Weekend Cuisine**: American  
- **Orders costing more than $20**: ~29%  
- **Unrated Orders**: 736 orders  

---

### Multivariate Analysis
- Relationship between cost, ratings, preparation time, and delivery time
- Comparison of delivery times on weekdays vs weekends
- Cuisine-wise preparation time analysis
- Day-of-week vs cuisine order patterns

---

## Business Questions Answered

- Mean food preparation time: **~27.4 minutes**
- Mean delivery time: **~24.2 minutes**
- Orders taking more than 60 minutes (prep + delivery): **~10.5%**
- Weekend deliveries are **faster than weekdays**
- Identified restaurants eligible for promotional offers based on:
  - Rating count > 50
  - Average rating > 4

### Restaurants Eligible for Promotion
- Blue Ribbon Fried Chicken  
- Blue Ribbon Sushi  
- Shake Shack  
- The Meatball Shop  

---

## Revenue Analysis
FoodHub revenue model:
- 25% commission on orders > $20
- 15% commission on orders > $5

**Total Net Revenue Generated**: **$6,166.30**

---

## Conclusions
- American cuisine dominates weekend demand
- High-rated restaurants also receive higher order volumes
- Delivery times are shorter on weekends
- A small but notable percentage of orders exceed acceptable delivery time thresholds

---

## Recommendations
- **Optimize weekday delivery operations** to reduce delays
- **Promote high-performing restaurants and cuisines**
- **Leverage customer ratings** to guide promotions
- **Introduce loyalty discounts** for frequent customers
- **Segment customers** based on ordering behavior for targeted marketing

---

## Project Structure
```
FoodHubOrder_Analysis/
├── foodhub_order.csv
├── FoodhubOrder_analysis.ipynb
├── README.md

```
