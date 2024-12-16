# Supply Chain & Inventory Management
## Objective
Analyze supply chain and inventory management using Sales_Shipment_Data and Inventory_Stock_Data to improve efficiency, identify trends, and derive actionable insights.
## Overview
The analysis encompasses data audit, cleaning, exploratory data analysis (EDA), and data preparation for predictive modeling. It aims to address specific business questions, such as identifying delivery trends, inventory optimization, and profitability insights. The project also involves building predictive models to forecast sales, along with creating visualizations to effectively communicate the findings. The ultimate goal is to enhance operational efficiency and provide actionable recommendations based on data-driven insights.
## Dataset Used
#### <a href="https://github.com/SourabhaSekharRout/Supply-Chain-Inventory-Management/blob/main/Sales_Shipment_Data.zip">Sales_Shipment_Data</a>:
- Contains details on orders, customers, products, and shipments.
#### <a href="https://github.com/SourabhaSekharRout/Supply-Chain-Inventory-Management/blob/main/Inventory_Stock_Data.csv">Inventory_Stock_Data</a>:
- Provide inventory-specific details.
## Process
- Data Import
  - Load datasets using Python libraries.
- Data Audit
  - Inspect shape, column types, and missing values.
  - Identify cleaning and preparation needs.
- Data Cleaning
  - Rename columns to follow conventions.
  - Convert data types and impute missing values.
  - Handle outliers and duplicates.
- Data Merge
  - Combine datasets using Product Id.
- EDA
  - Univariate and bivariate analysis to identify trends and correlations.
- Data Preparation
  - Create Late Delivery Risk flag.
  - Aggregate data for high-level metrics.
- Predictive Modeling
  - Build a sales forecasting model using linear regression.
  - Aggregate data at the customer level.
## Questions Addressed
#### a. Data Audit: Calculate Below metrics (Weightage - 10%)
1. Number of rows & Number of columns
2. Number of numerical & categorical columns
3. Any other observations from the data in terms of cleaning, preparation required?
4.  Detailed EDA - Univariate & Bi Variate analysis for each variable (distributions)
5. Find out data related issues based on the data Audit
#### b. Data Preparation: (Weightage - 15%)
1. Creat new flag variable Late Delivery Risk based on Days for shipping (real) & Days for shipment (scheduled) (Flag=Not Late if shipment is not delayed and Flag=Late if shipment is delayed)									
2. Rename the variables as per python naming convensions									
3. Convert the variables data types as per the data descriptions									
4. Impute missing values with mean for numerical variables, mode for categorical variables					
5. Perform any other data preparation steps as required?									
#### c. List of Analysis: (weightage - 40%)
1. Caclulate high level metrics like, total sale value, total sale units, inventory value, inventory quantity, profit value, number of distinct products, number of distinct categories, number of distinct products etc							
2. Status of orders (number of orders by current status)									
3. Status of Delivery of orders (number of orders by each type of delivery status)							
4. Late Delivery Risk by time (by each week, month, year, quarter)									
5. Order Item qty by time (by each week, month, year, quarter)									
6. Sales units/value  by time (by each week, month, year, quarter)									
7. Profit orders/value  by time (by each week, month, year, quarter)									
8. Order profit per order  by time (by each week, month, year, quarter)									
9. Order count by country/state/  by time (by each week, month, year, quarter)								
10. Inventory Units by each class or cluster									
11. Inventory Value by each class or cluster									
12. inventory by class									
13. Detail Stock Action (products to be ordered, not required to ordered)								
14. Product Order qty trend  (by time (by each week, month, year, quarter))					
15. Top 10 Most ordered products/Top 10 Most Categories/Top 10 cities interms of revenue and sale units (quantity)
16. Top payment methods by each product category.									
17. Which shipping mode is more efficient interms of not delaying?									
18. Number of orders, sales, qty  by order status									
19. Which categories are most profitable categories (top5)?									
20. Which categoires have been given highest average discount (top5)?									
21. Any other analysis you can perform? (At least 5 additional analysis you required to work on beyond the supported questions)
#### d. Create visualizations of the analysis (as per Sample reports provided - you need to create only charts and dashboard is optional) (Weightage - 15%)
1. Sample report & metrics provided as reference. However, you can come up with your own charts/visualizations as required. You can come up with the codes to replicate the charts/visualizations.
2. The data used for the sample reports is different than the data provided for this case study so the numbers may not be same
3. Any other visualizaitons (at least 2) you can create beyond visualizaitons mentioned in the sample reports & metrics?
#### e. Predictive modeling & perform the tasks as per your understanding (Weightage: 20%)
1. Build predictive model to predict the sales (Hint: You are required to aggregate the data at customer level. It means that one record for one customer)
2. Prepare end to end code with proper comments
3. Derive insights as per the models
## Features
- Order Item Total, Sales, Delivery Status, Shipping Mode.
- Inventory details: Current Stock, Reorder Point.
- Late Delivery Risk: Delivery delay flag.
- Aggregated metrics by time and geography.
## Insights
- Operational Efficiency: Trends in late deliveries and delay causes.
- Profitability: Most and least profitable categories/products.
- Inventory Optimization: Reorder points and safety stock suggestions.
- Customer Behavior: Spending trends and preferences.
