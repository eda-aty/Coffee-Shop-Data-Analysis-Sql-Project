
## ☕Coffee Shop Sales Analysis with SQL

# Table of Contents
* [Project Overview](#project-overview)
* [DataSet](#dataset)
* [Tools and Methodology](#tools-and-methodology)
* [Project Objectives](#project-objectives)
* [EDA and Business Tasks](#eda-and-business-task)
* [Dashboard](#dashboard)
* [Key İnsights](#key-insights)
* [Recommendations](#recommendations)



# 🎯 Project Overview:
I developed a SQL-based analysis using PostgreSQL to extract actionable insights from Maven Roastery coffee shop sales data. This project is focused on querying and analyzing, and aims to produce data-driven strategies for sales marketing, customer segmentation, and consumption efficiency. This project analyzes the sales transactions from a coffee shop, stored in the Transactions table.

# Dataset :
This analysis is based on the coffee shop business from January 2023 - June 2023 in Kaggle  [here](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales).
Coffeshop dataset includes transaction records that include details about transactions and products, including transaction ID, sales date/time, product type and detail, product categories, transaction count, unit price, store location. 




# 🛠️  Tools and Methedology: PostgreSQL, LookerStudio

- **Data Collection**: Kaggle data set

- **Data transformation**: Data cleaning using Postgresql queries 

- **Performed data modelling** : Using  PostgreSQL to analyse transactions table in a dataset

- **KPI’S determaning**: Total sales, Total orders, Total transactions quantity

- **Adding sql queries**: Solved some business problems and extracting Month, Day, Hour, and Day of Week from transaction_date and transaction_time. 

- **Data visualization**:  Using Looker Studio which included project objectives


# 🔧 Project Objectives:

📈  Sales & Revenue Analysis

📅  Time Series & Trend Analysis

🛍️ Product Performance

🌍  Store ( Location) Analysis

🔍 Filters and Visualizations

📄 Insights and Recommendations

# Dashboard:
The interactive Looker Studio Dashboard can be viewed [here](https://lookerstudio.google.com/s/rOovr7ZG6aU).

# 📊 Key İnsights:

- From the analysis above, it can be seen that the coffee shop received **149,116 orders** in 2023. This resulted in over** 214 thousand units of products sold**, generating a **total revenue of $698,812**.


- From the above analysis **Coffee**, **Tea**, **Bakery** categories contribute the most to the total sales but **” Pacakage Chocolate** is the least performing category.


- **Brewed Chai Tea** is the most sold product, and apart from the coffee and tea category, **Hot Chocolate** is a product type that stands out with a different category. It may be useful to take into consideration when organizing campaigns for customers regardless of the categories.

- **Top selling products by  total_qty_sold**:

"Brewed Chai tea" : 26250
"Gourmet brewed coffee" : 25973
"Barista Espresso" : 24943
"Brewed Black tea" : 17462
"Hot chocolate"	: 17457

- Each store generated over $200,000 in sales. **“Hell’s Kitchen”** led the way with $236,511, accounting for 33.8% of total sales.

- The products in the top three categories have an average price of $20, and the product with the highest unit price appears to be coffee beans, with price differences depending on the branch.
- There is an upward trend in sales throughout the months, except for a decline in sales in February.
Most of the sales occur on weekends. In addition, the highest sales of the month were achieved in the "Hell's Kitchen" store on the 13th day of the month.
Orders seem to peak between **7am - 10am**. The highest sales traffic occurs at 10am, then begins to decline, reaching its lowest point around 8pm.

- The product with the highest unit price is **“Premium Beans”** and it makes a very high contribution to the coffee shop’s income by selling 496 units. 
**Chai Tea**, on the other hand, is the product with the lowest unit price, but its sales amount is 443 units, which is a very high number, and as seen in the above analyses, the tea category was the second category that made the highest contribution to the total sales.

- The product with the highest average revenue in the **"Astoria"** store is **Premium Beans** with $32, while in the **"Hell's Kitchen"** store,** "Premium Beans"** is at the top with an average revenue of $57, and in the **"Lower Manhattan"** store, **"Premium Beans"** is again at the top with $34.

- The **"Green beans"** product has the lowest sales performance with a sales volume of 134 units and a sales revenue of $1,340.


# 📄  Recommendations:

-  **Take Advantage of Rush Hours** : It is important to have adequate staff and stock distribution for increased rush hours on **Monday** and **Friday**, especially from 7am to 10am, which is the busiest time to distribute. It may also be a good idea to plan marketing campaigns and promotions for these components of the morning rush hours.


-  **Increase Your Order Efficiency**: Since the order volume of specialty coffee beans is high, you can experiment with stand promotions, tasting hours or promotions specific to these products to increase your income and profitability, and you can also get a better data analysis opportunity by obtaining new data.


-  **Create a customer loyalty program** : Create a marketing program for your target audience, which consists of customers who provide regular orders or have a fixed contribution to your sales. In this way, you can have the opportunity to get to know them in more detail with titles such as gender, age, preference details and create more profit and customer loyalty.

-  **Develop location-specific social media strategies** : You can run location-based social media ads or try to multiply your sales revenues by running a package campaign with another suitable product along with the most ordered product, such as **"Dark chocolate Lg"**  in the Astoria location.










