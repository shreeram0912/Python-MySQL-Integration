# Python-MySQL-Integration
 **Project Overview: Data Analysis on DmartReady Online Store**

Title: Data Analysis Project on DmartReady Online Store
Subtitle: Leveraging SQL and Python for Insights
Date: 14-Jan-2025


### Introduction:

What is DmartReady?
An online platform for purchasing groceries and other essentials.

- The DmartReady Online Store Analysis is a comprehensive data-driven project aimed at understanding the operational, financial, and customer behavioral patterns of DmartReady, an online retail platform. 
- The analysis leverages SQL and Python to extract, transform, and analyze large datasets, providing valuable insights into sales trends, customer demographics, product performance, and operational efficiency. 
- By examining key metrics such as total sales, order volumes, customer engagement, and marketing performance, the project identifies factors influencing the business's growth and profitability.
  

### Objectives:
To analyze customer behavior, sales trends, and product performance using SQL and Python.

The primary objectives of this analysis include:

* Understanding Sales Performance: Analyze total and average sales, sales by category, and revenue contribution by gender and marketing campaigns.
* Customer Behavior Analysis: Study customer demographics, average time spent on the website, and buying patterns by state, city, and age group.
* Product Analysis: Identify top-performing products, products with the highest discount rates, and products with the highest customer engagement.
* Operational Efficiency: Evaluate delivery times, ship modes, and cancellation rates across states and cities to improve logistics.
* Marketing Insights: Assess the effectiveness of different marketing platforms in driving sales and revenue.
* Profitability Assessment: Determine profit margins across various product categories.
  


### Project Outcomes:

+ Extract actionable insights to improve business strategies.
+ Understand customer preferences and optimize inventory.
+ Develop visualizations to present findings effectively.


### Data Sources:

Primary Data Source:
DmartReady transactional and product data.
https://www.kaggle.com/datasets/praneethkumar007/dmart-ready-online-store
Data Types:
Customer details.
Product catalog.
Sales records.
Order and delivery information.


### Tools and Technologies:

+- SQL: For querying and managing the database.
+- Python: Used for data integration with MySQL using mysql.connector library & For data manipulation and visualization using libraries like Pandas, Numpy, Matplotlib, Plotly, and Seaborn.
+- Jupyter Notebook: For organizing and executing the project.


### Challenges:

* Ensuring data accuracy and completeness.
* Managing large datasets efficiently.
* Integrating SQL and Python workflows seamlessly.

### Data Analysis Workflow:

**1.Data Collection:**
Extract data using SQL queries.

**2. Data Cleaning:**
Handle missing values and inconsistencies using Python.

**3. Exploratory Data Analysis (EDA):**
Analyze trends, outliers, and patterns.

**4. Visualization:**
Create charts and graphs to represent insights.

**5. Reporting:**
Summarize findings and suggest recommendations.


### Visualization
![image](https://github.com/user-attachments/assets/4290b823-1528-4c01-83df-8ba1591ba06f)
![image](https://github.com/user-attachments/assets/3f4fedca-42d2-48b3-ae97-8dfa79f3c85a)
![image](https://github.com/user-attachments/assets/317d8d68-e27d-4fc4-b88d-5f29c149836b)
![image](https://github.com/user-attachments/assets/8de2db4f-177d-45d5-bf12-d69e12befe73)
![image](https://github.com/user-attachments/assets/74c731c8-9b1c-491d-ac3f-cd7b29dfb40a)
![image](https://github.com/user-attachments/assets/93c11b37-cec7-482c-af0e-12b9d91b308c)
![image](https://github.com/user-attachments/assets/dfbaa409-31bd-4baa-90d5-953750ccc211)
![image](https://github.com/user-attachments/assets/3e4c061d-d84d-41c8-91de-464a4da5c158)
![image](https://github.com/user-attachments/assets/0c082f64-4031-4b08-9320-a2d240195634)
![image](https://github.com/user-attachments/assets/aa05a959-7f86-4d57-96c8-0bf6d420bb83)
![image](https://github.com/user-attachments/assets/4546e936-bbca-478a-82ab-45bd29b00434)



### Key Insights Expected:

High-demand products and their sales trends.
Seasonal variations in purchasing patterns.
Customer segmentation and their buying behavior.
Inventory gaps and delivery performance.


### Sales Insights

**Total Sales:**
The store generated total sales of ₹16,954,109 over the analyzed period.
Average sales per order are ₹678.16, indicating moderate order values.

**Yearly Performance:**
Sales have remained steady across years, with slight peaks in 2022 at ₹5,729,150.56.
Orders have grown from 8,310 in 2021 to 8,365 in 2023, suggesting slight growth in demand.

**Monthly Trends:**
November and December consistently show higher sales and orders, likely due to festive shopping.
February and September have lower sales and order volumes across years, indicating potential off-seasons.

**Category Performance:**
Local products contribute the most to sales (₹8,482,035) and profit (₹4,557,246.29), emphasizing customer preference for local goods.
Branded products are the second-best performer.

### Customer Behavior

**Gender-Based Insights:**
Male customers contribute more to sales, especially in the 26-45 age group.
Males are the primary audience for Instagram and Facebook campaigns.

**State and City Analysis:**
Maharashtra, Andhra Pradesh, Gujarat, and Telangana are top-performing states, with Maharashtra leading sales at ₹4,298,237.
Top cities like Suryapet, Vadodara, and Guntur have significant contributions to overall sales.

**Time Spent on the Website:**
Andhra Pradesh customers spend the most time online (10.50 minutes on average).
Cities like Ramagundam, Vijayawada, and Karimnagar have the highest engagement levels.


### Product Performance

**Top-Selling Products:**
Household essentials like Harpic Bathroom Cleaner and Parle Nutricrunch Digestive Cookies are top contributors to sales.
Products with higher engagement also show high average time spent, such as Ariel Matic Top Load Liquid Detergent.

**High Discount Products:**
Products like Nimyle Herbal Anti-Bacterial Floor Cleaner and Tata Tea Chakra Gold Premium
Tea offer the highest discounts (95%), driving sales but potentially affecting margins.

**Profitability:**
Local and branded products contribute significantly to profits, emphasizing a balance between cost and demand.


### Operational Insights

**Delivery Efficiency:**
Most deliveries occur within 2-10 days, with a need to improve delivery times for orders taking over a week.
Free shipping generates the most revenue, but priority and express plus shipping are growing contributors.

**Payment Preferences:**
Debit cards are the most popular payment method, followed by credit cards.
COD (Cash on Delivery) contributes the least, indicating digital payment adoption.

**Cancellation Rates:**
Andhra Pradesh and Gujarat cities like Anantapur and Bhavnagar have high cancellation rates, signaling potential issues with customer satisfaction or delivery logistics.


### Marketing Effectiveness

**Top Platforms:**
Instagram campaigns yield the highest revenue (₹5,755,979), especially among male customers.
Facebook and referrals from friends also perform well, while TV ads are the least effective.

**Gender-Specific Campaigns:**
Male customers engage more with Instagram, while female customers respond better to Facebook and referral campaigns.


### Recommendations

**Seasonal Campaigns:**
Focus on November and December with targeted marketing campaigns and attractive discounts to maximize festive demand.

**Improve Delivery Times:**
Reduce delays for longer delivery periods to improve operational efficiency and customer satisfaction.

**Optimize Discounts:**
Reassess high-discount strategies for products contributing low profitability while promoting profitable items.

**City-Specific Strategies:**
Address high cancellation rates in cities like Anantapur and Bhavnagar by improving customer communication and delivery reliability.

**Leverage Top Platforms:**
Double down on Instagram and Facebook campaigns for male audiences while exploring other platforms for female engagement.


### Thank You!
Questions or Feedback?
Contact: @shreeram0912
