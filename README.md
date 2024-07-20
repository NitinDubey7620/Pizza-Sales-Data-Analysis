# Pizza-Sales-Data-Analysis

Overview:-
This project employs SQL to examine pizza sales data, with the goal of identifying sales patterns, customer preferences, and business performance metrics. The analysis is conducted using a MySQL database named "pizzamania".

Database Structure:-
The "pizzamania" database is composed of four main tables:

1.pizzas Table

pizza_id: Unique identifier for each pizza.
pizza_type_id: Identifier for the type of pizza.
size: The size of the pizza (e.g., small, medium, large).
price: The price of the pizza.

2.orders Table

order_id: Unique identifier for each order.
order_time: The time the order was placed.
order_date: The date the order was placed.

3.order_details Table

order_id: Links to the corresponding order.
pizza_id: Links to the specific pizza ordered.
quantity: The number of pizzas ordered.
order_details_id: Unique identifier for each order detail entry.

4.pizza_types Table

pizza_type_id: Unique identifier for each pizza type.
name: The name of the pizza type.
category: The category of the pizza (e.g., vegetarian, non-vegetarian).
ingredients: The ingredients used in the pizza.

Analysis Questions:-

Basic

1.Calculate the total number of orders.
2.Determine the total revenue from pizza sales.
3.Find the highest-priced pizza.
4.Identify the most frequently ordered pizza size.
5.List the top 5 most ordered pizza types and their quantities.

Intermediate

6.Aggregate data to find the total quantity of pizzas ordered by category.
7.Analyze the distribution of orders by hour.
8.Aggregate data to show the distribution of pizza orders by category.
9.Calculate the average number of pizzas ordered per day.
10.Identify the top 3 most ordered pizza types by revenue.

Advanced

11.Calculate the percentage revenue contribution of each pizza type.
12.Examine the cumulative revenue over time.
13.Identify the top 3 most ordered pizza types by revenue within each category.

Presentation:-

The results and insights from this analysis are presented in a PowerPoint presentation included in this repository.


