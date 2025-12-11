# Credit_Card_Financial_Dashboard

Credit Card transaction and customer weekly report using PowerBI and SQL

<br>

Project Objective :
To develop a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.

<br>

🛠 Key Steps Followed ;

1. Prepared the CSV files and created structured tables in SQL.

2. Imported the CSV data into SQL for preprocessing.

Loaded the cleaned SQL tables into Power BI for modeling and visualization.

3. Used SWITCH() to create calculated columns such as Age Group and Income Group.

4. Applied key DAX functions like WEEKNUM(), CALCULATE(), SUM(), and FILTER() to derive
Current Week Revenue and Previous Week Revenue.


<br>

📌 Key Insights + Key recommendations

 1. Strong Weekly Revenue Trend by 28.8% as of last week 53%

 2. Age group 40–60 = Strongest Revenue Segment
This group drives the highest consistent revenue.

3. White Collars & Businessmen = High Performers
These two profession segments contribute the majority of revenue and interest.

4. Male customers are contributing more in revenue 31 M while female 26 M

5. Blue and Silver Credit cards contributing to 93% of overall Transactions 
Blue cards generate the highest revenue (47M+) across all categories.

 6. Swipe Transactions Lead by a Big Margin
Clear preference for physical card usage.

 7. Top States - TX, NY, CA remain the strongest revenue markets contributing to 68% 

8. Overall Activation rate is 57.5% 

9. Overall Delinquent rate is 6.06% 

10. Graduates generate the highest revenue → 23M.

<br>

🔐 Key recommendations ;

1. Soft Monitoring for High-Risk Professions -
Self-employed and business owners have income volatility.
A 30%+ drop in monthly spend should trigger an early-warning monitoring band.

Send a light alert to the risk team to observe behaviour for 30 days —
no collections, just monitoring.
This quietly prevents future potential NPAs.

2. Strengthen Retention for High-LTV Segments

Graduates and Businessmen contribute the highest revenue.
Introduce micro-segment rewards:

Graduates → EdTech, OTT, food delivery

Businessmen → Travel, hotel, fuel 
This increases stickiness and long-term value. 

3. Double Down on Top Revenue States (TX, NY, CA)

These states are already strong performers.
Launch localized merchant partnerships with fuel stations, grocery chains, and retail stores.
High volume impact with low cost.

4. Strengthen Fraud Protection on High-Value Swipes

Swipe transactions above 20,000 should trigger an instant SMS + push notification.

A quick “Did you make this transaction?” validation adds zero-cost, high-impact fraud prevention.
