# PIZZA-HUT-SALES-ANALYSIS-SQL-


Problem Statement

This project analyzes pizza sales data from multiple sources. The dataset consists of four CSV files:

orders.csv – contains order date and time

order_details.csv – contains order quantity and pizza IDs

pizzas.csv – contains pizza size and price

pizza_types.csv – contains pizza category and names

The main objective is to merge these datasets into a single unified dataset and perform analysis to uncover meaningful business insights such as sales trends, customer preferences, and product performance.

🔗 Data Integration Process

Combined datasets using common keys:

order_id → (orders & order_details)

pizza_id → (order_details & pizzas)

pizza_type_id → (pizzas & pizza_types)

Created a final dataset containing:

Order date & time

Pizza name & category

Size & price

Quantity & total revenue

📊 Key Insights

 Sales by Category
 
Classic category is the most sold

Chicken category is the least sold

Size Preference

Customers mostly prefer Large (L) size pizzas

 Top & Least Selling Pizzas
 
Top selling pizza: The Classic Deluxe Pizza

Least selling pizza: The Brie Carre Pizza

 Pricing & Quantity
 
Average selling price of pizza ≈ $37

Average order quantity ≈ 2 pizzas per order

Customer Behavior

Highest orders on Fridays

Lowest orders on Sundays

 Peak Order Time
 
Most orders are placed between 12:00 PM – 1:00 PM (Lunch time)

 Conclusion
 
The analysis reveals that customer preferences are strongly influenced by pizza category, size, and time of purchase. Businesses can leverage these insights to:

Focus on promoting high-demand categories like Classic

Optimize inventory for Large-size pizzas

Offer discounts during low-demand periods (e.g., Sundays)

Prepare for peak hours (12–1 PM) to improve service efficiency


