🛒 Amazon Brazil E-Commerce SQL Analysis

📌 About the Project

This is a SQL project based on the Brazilian E-Commerce dataset from Olist.

I used SQL to explore the data and look at different parts of an e-commerce business, including orders, customers, products, sellers, payments, delivery and customer reviews.

The main goal of the project was to practice SQL with a real-world dataset and answer some business-related questions using the available data.

🗃️ Dataset

The dataset contains around 100K orders from the Brazilian e-commerce marketplace between 2016 and 2018.

For this project, I worked with these tables:

| Table                               | Description                   |
| ----------------------------------- | ----------------------------- |
| `olist_orders_dataset`              | Order details and status      |
| `olist_order_items_dataset`         | Products included in orders   |
| `olist_order_payments_dataset`      | Payment information           |
| `olist_order_reviews_dataset`       | Customer reviews              |
| `olist_products_dataset`            | Product information           |
| `olist_customers_dataset`           | Customer information          |
| `olist_sellers_dataset`             | Seller information            |
| `olist_geolocation_dataset`         | Location information          |
| `product_category_name_translation` | Product category translations |

🔎 Questions I Explored

Some of the questions I worked on were:

* How many orders were placed?
* How did the number of orders change over time?
* Which product categories had the most sales?
* Which sellers had the highest sales?
* Where were most customers located?
* Which payment methods were used most often?
* How much were customers spending?
* How long did orders take to reach customers?
* What did the customer review scores look like?
* Was there any connection between delivery time and customer reviews?

📊 Analysis

📦 Order Analysis

I looked at the number of orders and how they changed over time.

This includes:

* Total orders
* Orders by year and month
* Order status
* Delivered orders
* Cancelled orders

💰 Sales Analysis

I used the order items and payment data to look at sales.

Some of the things I checked were:

* Total sales
* Sales by category
* Sales by seller
* Average order value
* Product prices
* Freight charges

🛍️ Product Analysis

I explored the products and categories to see what customers were buying.

This includes:

* Number of products
* Product categories
* Most purchased categories
* Sales by category
* Product prices
* Freight values

👥 Customer Analysis

I looked at customer data to understand purchasing patterns and locations.

This includes:

* Number of customers
* Customers by state
* Orders per customer
* Customer spending
* Customer locations

🏪 Seller Analysis

I compared sellers based on their orders, products and sales.

This includes:

* Number of sellers
* Orders handled
* Products sold
* Sales generated
* Seller locations
* Top sellers

💳 Payment Analysis

I looked at the payment data to understand how customers paid for their orders.

This includes:

* Payment methods
* Credit card payments
* Debit card payments
* Vouchers
* Payment values
* Number of installments

🚚 Delivery Analysis

I used the order date information to look at delivery performance.

I checked:

* Order-to-delivery time
* Estimated vs actual delivery
* Delayed deliveries
* Delivery performance by location

⭐ Review Analysis

I also looked at customer review scores to get an idea of customer satisfaction.

This includes:

* Review score distribution
* Average review score
* Reviews by category
* Reviews by seller
* Delivery time and review scores

🧮 SQL Skills Used

Some of the SQL concepts I used in this project:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `HAVING`
* `DISTINCT`
* `CASE`
* `JOIN`
* `LEFT JOIN`
* Aggregate functions
* Subqueries
* CTEs
* Window functions
* Date functions
* String functions

💡 What I Found

Working with the data helped me get a better understanding of:

* 📈 Order and sales trends
* 🛒 Customer purchasing patterns
* 🏆 Popular product categories
* 🏪 Seller performance
* 💳 Payment preferences
* 🚚 Delivery patterns
* ⭐ Customer reviews
* 🌎 Customer and seller locations

The detailed results and numbers are available in the SQL queries and the project presentation.

📂 Project Structure

```text
Amazon-Brazil-SQL-Analysis/
│
├── data/
│
├── sql/
│   ├── data_exploration.sql
│   ├── customer_analysis.sql
│   ├── sales_analysis.sql
│   ├── product_analysis.sql
│   ├── seller_analysis.sql
│   ├── payment_analysis.sql
│   ├── delivery_analysis.sql
│   └── review_analysis.sql
│
├── presentation/
│   └── Amazon_Brazil_SQL_Analysis.pptx
│
└── README.md
```

🚀 How to Use

1. Clone or download the repository.
2. Import the Olist CSV files into your SQL database.
3. Create the required tables.
4. Run the SQL queries from the `sql` folder.
5. Check the results and compare them with the presentation.

📚 What I Learned

This project gave me more practice working with SQL and multiple related tables.

I got more comfortable with joins, aggregations, CTEs, window functions and using SQL to answer business questions.

I also learned how different parts of an e-commerce business are connected through customer, order, product, seller and payment data.

👨‍💻 About Me

Shubham Paitwar

Mechanical Engineer | Data Analyst

Skills: SQL, Python, Power BI, Excel, Pandas, NumPy, Matplotlib

🔗 Connect With Me

* GitHub: https://github.com/Shubhampaitwar
* LinkedIn: www.linkedin.com/in/shubham-paitwar-8048a9252

---

📌 This project was created for learning and portfolio purposes using the publicly available Olist Brazilian E-Commerce dataset.
