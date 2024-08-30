# Zomato Data Analysis Project

This project focuses on analyzing customer behavior and restaurant performance data from Zomato. The analysis involves exploring customer spending habits, restaurant ratings, and the impact of online and offline ordering modes. The goal is to provide insights that can help Zomato enhance its customer experience and optimize its restaurant partnerships.

## Project Overview

Zomato is a leading food delivery service with an average of 17.5 million monthly transacting customers. The platform has also seen a year-on-year increase of 8.7% in the average number of active restaurant partners, from 208,000 to 226,000. This project leverages customer and restaurant data to explore various aspects of Zomato's business.

### Key Objectives

1. Explore customer ordering patterns: Identify the types of restaurants that receive the most orders and analyze customer preferences.
2. Analyze customer spending: Understand the average spending by customers, especially couples, and determine the factors influencing it.
3. Evaluate restaurant performance: Examine the ratings and votes received by different types of restaurants and analyze the impact of online vs. offline ordering.
4. Provide actionable insights: Offer recommendations to Zomato for enhancing customer satisfaction and restaurant engagement.

## Data Description

The dataset used for this analysis contains the following columns:

- **name**: Name of the restaurant.
- **online_order**: Indicates if the restaurant accepts online orders ('Yes' or 'No').
- **book_table**: Indicates if the restaurant allows table bookings ('Yes' or 'No').
- **rate**: Customer rating of the restaurant.
- **votes**: Number of votes received by the restaurant.
- **approx_cost(for two people)**: Approximate cost for two people at the restaurant.
- **listed_in(type)**: Type of restaurant (e.g., Buffet, Dining, Cafes).

## Data Analysis and Visualizations

The analysis is divided into several key questions:

1. What type of restaurant do the majority of customers order from?
   - Identified that the majority of customers prefer dining restaurants.

2. How many votes has each type of restaurant received from customers?
   - Dining restaurants received the maximum number of votes.

3. What are the ratings that the majority of restaurants have received?
   - Most restaurants received ratings between 3.5 to 4.0.

4. What is the average spending on each order by couples?
   - The analysis revealed the spending distribution among couples, with a focus on online orders.

5. Which mode (online or offline) has received the maximum rating?
   - Online orders have higher ratings compared to offline orders.

6. Which type of restaurant received more offline orders?
   - Identified specific types of restaurants with a higher number of offline orders for targeted offers.

## Visualizations

The project includes several visualizations to support the analysis:

- Countplots to show the distribution of restaurant types and customer preferences.
- Line plots to visualize the votes received by each type of restaurant.
- Histograms and box plots to analyze ratings and spending patterns.
- Heatmaps to examine the relationship between restaurant types and order modes.

## Conclusion

This project provides valuable insights into customer behavior and restaurant performance on Zomato's platform. The findings can help Zomato optimize its services, improve customer satisfaction, and offer better-targeted promotions to its users.

## Getting Started

To run this analysis:

1. Clone this repository
2. Install the required libraries: `numpy`, `pandas`, `seaborn`, and `matplotlib`.
3. Load the dataset and run the analysis scripts provided in the repository.

## License

This project is licensed under the MIT License.

