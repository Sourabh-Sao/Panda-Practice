# Daily Pandas Practice

Repository for daily Pandas queries and visualization exercises.

Purpose:  
Improve data analysis skills through consistent practice with real-world-like e-commerce data.

Dataset: `ecommerce_clean.csv` – simulated e-commerce orders data with 39 columns (customers, products, sales, profit, shipping, etc.)


This repo uses a simulated e-commerce orders dataset containing the following columns:

| Column                | Description                              |
|-----------------------|------------------------------------------|
| order_id             | Unique order identifier                  |
| order_date           | Date when order was placed               |
| delivered_date       | Date when order was delivered            |
| customer_id          | Unique customer identifier               |
| customer_name        | Full name of customer                    |
| customer_age         | Age of customer                          |
| customer_gender      | Gender (Male/Female/Other/Prefer not to say) |
| customer_segment     | Customer type (Consumer, Corporate, Home Office, etc.) |
| region               | Broad geographic region                  |
| state                | State/Province                           |
| city                 | City                                     |
| product_id           | Unique product identifier                |
| product_name         | Name of the product                      |
| category             | Main product category                    |
| sub_category         | Sub-category of product                  |
| brand                | Brand name                               |
| unit_price           | Price per unit (before discount)         |
| quantity             | Number of units ordered                  |
| discount_percentage  | Discount % applied                       |
| discount_amount      | Absolute discount amount                 |
| sales_amount         | Revenue after discount (quantity × discounted price) |
| profit_margin        | Profit margin percentage                 |
| profit_amount        | Actual profit earned on this order line  |
| tax_rate             | Applicable tax rate                      |
| tax_amount           | Tax amount                               |
| shipping_cost        | Shipping charges                         |
| shipping_method      | Delivery mode (Standard, Express, etc.)  |
| total_amount         | Final amount paid by customer            |
| payment_method       | Payment type (Cash, Card, UPI, etc.)     |
| delivery_time_days   | Days taken to deliver                    |
| order_status         | Delivered / Cancelled / Returned / etc.  |
| rating               | Customer satisfaction rating (1–5)       |
| is_repeat_customer   | Boolean – has this customer ordered before? |
| order_year           | Extracted year                           |
| order_month          | Extracted month (1–12)                   |
| order_quarter        | Extracted quarter (1–4)                  |
| order_day_of_week    | Day of week (Monday=0 … Sunday=6)        |


## Tools / Libraries

- pandas
- numpy
- matplotlib
- seaborn
- jupyter notebook

## Start date
**January 28, 2026**

Feel free to use the same dataset and follow along.
