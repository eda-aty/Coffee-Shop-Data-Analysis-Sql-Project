
## ☕Coffee Shop Sales Analysis with SQL

Table of Contents:
* [Project Overview](#Project-Overview]
* [DataSet](#data-set)
* [Tools and Methodology](#tools-and-methodology)
* [Project Objectives](#project-objectives)
* [EDA and Business Tasks](#eda-and-business-task)
* [Dashboard](#dashboard)
* [Key İnsights](#key-insights)
* [Recommendations](#recommendations)



### 🎯 Project Overview:
I developed a SQL-based analysis using PostgreSQL to extract actionable insights from Maven Roastery coffee shop sales data. This project is focused on querying and analyzing, and aims to produce data-driven strategies for sales marketing, customer segmentation, and consumption efficiency. This project analyzes the sales transactions from a coffee shop, stored in the Transactions table.

## Dataset :
This analysis is based on the coffee shop business from January 2023 - June 2023 in Kaggle.
Coffeshop dataset includes transaction records that include details about transactions and products, including transaction ID, sales date/time, product type and detail, product categories, transaction count, unit price, store location. 




## 🛠️  Tools and Methedology: PostgreSQL, LookerStudio
#Data Collection: Kaggle data set
#Data transformation: Data cleaning using Postgresql queries 
#Performed data modelling : Using  PostgreSQL to analyse transactions table in a dataset
#KPI’S determaning: Total sales, Total orders, Total transactions quantity
#Adding sql queries: Solved some business problems and extracting Month, Day, Hour, and Day of Week from transaction_date and transaction_time. 
#Data visualization:  Using Looker Studio which included project objectives


## 🔧 Project Objectives:
📈  Sales & Revenue Analysis
📅  Time Series & Trend Analysis
🛍️ Product Performance
🌍  Store ( Location) Analysis
🔍 Filters and Visualizations
📄 Insights and Recommendations

## Dashboard:
You can reach this projects  Looker Studio Dashboard from  [here](https://lookerstudio.google.com/s/rOovr7ZG6aU).

## 📊 Key İnsights:

From the analysis above, it can be seen that the coffee shop received **149,116 orders** in 2023. This resulted in over** 214 thousand units of products sold**, generating a **total revenue of $698,812**.


From the above analysis **Coffee**, **Tea**, **Bakery** categories contribute the most to the total sales but **” Pacakage Chocolate** is the least performing category.


**Brewed Chai Tea** is the most sold product, and apart from the coffee and tea category, **Hot Chocolate** is a product type that stands out with a different category. It may be useful to take into consideration when organizing campaigns for customers regardless of the categories.

**Top selling products by  total_qty_sold**:

"Brewed Chai tea" : 26250
"Gourmet brewed coffee" : 25973
"Barista Espresso" : 24943
"Brewed Black tea" : 17462
"Hot chocolate"	: 17457

Each store generated over $200,000 in sales. **“Hell’s Kitchen”** led the way with $236,511, accounting for 33.8% of total sales.

The products in the top three categories have an average price of $20, and the product with the highest unit price appears to be coffee beans, with price differences depending on the branch.
There is an upward trend in sales throughout the months, except for a decline in sales in February.
Most of the sales occur on weekends. In addition, the highest sales of the month were achieved in the "Hell's Kitchen" store on the 13th day of the month.
Orders seem to peak between **7am - 10am**. The highest sales traffic occurs at 10am, then begins to decline, reaching its lowest point around 8pm.

The product with the highest unit price is **“Premium Beans”** and it makes a very high contribution to the coffee shop’s income by selling 496 units. 
**Chai Tea**, on the other hand, is the product with the lowest unit price, but its sales amount is 443 units, which is a very high number, and as seen in the above analyses, the tea category was the second category that made the highest contribution to the total sales.

The product with the highest average revenue in the **"Astoria"** store is **Premium Beans** with $32, while in the **"Hell's Kitchen"** store,** "Premium Beans"** is at the top with an average revenue of $57, and in the **"Lower Manhattan"** store, **"Premium Beans"** is again at the top with $34.

The **"Green beans"** product has the lowest sales performance with a sales volume of 134 units and a sales revenue of $1,340.


## 📄  Recommendations:

**Monday** and **Friday** günleri artan yoğunluğu yönetmek için yeterli personel ve stok tahsis etmeniz önemli ,özellikle sabah 7'den 10'a kadar olan en yoğun saatlerde. Yoğun satış saatleri sabah olduğundan bu saatlerde pazarlama kampanyalarını ve promosyonları düzenlemeyi düşünmek de iyi olabilir.


Özel kahve çekirdeklerinin sipariş miktarı yüksek olduğundan bu ürünlere özgü stand tanıtımı, tadım saatleri veya promosyonlar ekleyerek hem gelirinizi ve karlılığınızı arttırabilecek denemelerde bulunabilir hem de yeni veriler elde ederek daha iyi veri analiz şansı yakalayabilirsiniz.


Müşteri sadakat programı oluşturabilir, böylece hedef kitlenizi cinsiyet, yaş, tercih detayları gibi başlıklarla daha detaylı tanıma ve müşteri bağlılığı yaratma fırsatı bulabilirsiniz.


Lokasyon bazlı sosyal medya reklamları çıkarabilir veya Astoria lokasyonunda "Dark chocolate Lg" gibi en çok sipariş edilen ürün yanında başka uygun bir ürün eklenmesi ile paket kampanyası yaparak satış gelirlerinizi katlamayı deneyebilirsiniz.










