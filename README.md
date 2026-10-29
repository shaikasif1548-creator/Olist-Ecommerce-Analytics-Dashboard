# **🛒 Olist E-Commerce Analytics Dashboard**


## **Project Overview**

This project analyzes Brazilian e-commerce data from Olist to understand order performance, customer behavior, product performance, sales trends, and delivery operations.

The solution was developed using Microsoft Power BI to transform raw datasets into an interactive business intelligence dashboard. The project covers data preparation, data modeling, DAX calculations, KPI development, and visual analytics to support data-driven decision-making.



##### **📑 Table of Contents**


* ###### **Project Overview**
* ###### **Project Objective**
* ###### **Skills Demonstrated**
* ###### **Tools and Technologies**
* ###### **Dataset Overview**
* ###### **Dashboard Pages and Features**
* ###### **Key Performance Indicators**
* ###### **Data Preparation and Modeling**
* ###### **Data Visualization**
* ###### **Business Value**
* ###### **Dashboard Screenshots**
* ###### **Data Model**
* ###### **Key Business Takeaways**
* ###### **Project Limitations**
* ###### **Repository Structure**
* ###### **Business Insights**
* ###### **Conclusion**



#### **🎯 Project Objective**


The objective of this project is to transform raw e-commerce transaction data into actionable business insights using Microsoft Power BI.

The dashboard enables analysis of sales performance, customer behavior, product trends, payment methods, order fulfillment, and delivery efficiency to support data-driven decision-making.


###### **💡 Skills Demonstrated**


Data Cleaning and Transformation

Power Query

Data Modeling

DAX Measures and KPI Development

Business Intelligence Reporting

Dashboard Design

Exploratory Data Analysis (EDA)

Data Visualization

Performance Monitoring

Interactive Dashboard Development

###### 

###### **🛠️ Tools and Technologies**


Microsoft Power BI Desktop – Dashboard development and data visualization

Power Query – Data cleaning, transformation, and preparation

DAX (Data Analysis Expressions) – KPI calculations and analytical measures

Data Modeling – Establishing relationships between datasets for accurate analysis


###### **📊 Dataset Overview**


The project uses the Olist Brazilian E-Commerce Dataset, which contains information about orders, customers, products, sellers, payments, reviews, and geographic locations.


Source Datasets

Orders

Order Items

Customers

Products

Sellers

Payments

Reviews

Geolocation

Product Category Name Translation

These datasets are used to analyze customer behavior, sales performance, product categories, payment methods, order fulfillment, and delivery operations.


###### **📈 Dashboard Pages and Features**


**1. Overview Dashboard**


Displays key performance indicators including total orders, unique customers, total payment value, and delivered orders.

Analyzes monthly sales trends.

Shows the distribution of order statuses.

Compares payment value across payment methods.


**2. Customers Dashboard**


Analyzes customer distribution across states and cities.

Displays customer review score distribution.

Highlights the top 10 cities by customer count.

Includes state and city slicers for interactive filtering.


**3. Products Dashboard**


Analyzes product counts and product categories.

Displays product photo coverage and product dimension metrics.

Examines product weight distribution.

Identifies top product categories by item sales value.



**4. Sales Dashboard**


Tracks payment value, order volume, and average order value.

Analyzes monthly sales performance.

Compares payment value by payment type.

Examines order status and item sales value by seller state.


**5. Analytics Dashboard**


Monitors delivery rate and cancellation rate.

Analyzes average delivery time.

Tracks monthly order trends.

Compares average freight cost across seller states.

Includes interactive order status filtering.


###### **📌 Key Performance Indicators**


**KPI	                       Value**

Total Orders	               99,441

Unique Customers	           96,096

Delivered Orders	           96,478

Total Payment Value	         Approximately R$16.01 Million

Average Order Value	         Approximately R$160.99

Delivery Rate	               97.02%

Cancellation Rate            0.63%

Average Delivery Time	       12.50 Days

Total Products	             32,951

Products with Photos         32,341

Average Review Score	       4.09 / 5



These metrics help evaluate order fulfillment, customer activity, payment performance, product coverage, customer satisfaction, and delivery efficiency.



**Note**: Payment value represents recorded customer payments in the dataset and should not automatically be interpreted as revenue, profit, or business earnings.



###### **🔄 Data Preparation and Modeling**



**Data Preparation**



Imported the Olist source datasets into Power BI.

Used Power Query to prepare and transform the data.

Reviewed and corrected column data types.

Created delivery duration calculations using order purchase and delivery dates.



**Data Modeling**



Established relationships between Orders, Order Items, Customers, Products, Sellers, Payments, Reviews, and Product Category Translation tables.

Used order identifiers and relevant business keys to connect related datasets.

Kept the Geolocation dataset separate because it was not required in the dashboard model.



**DAX and Business Metrics**



Created measures for:



Total Orders

Unique Customers

Total Payment Value

Average Order Value

Delivered Orders

Delivery Rate

Cancellation Rate

Average Delivery Time

Additional modeling techniques included:



Distinct count calculations to avoid duplicate records.

Date-based analysis for monthly trends.

Interactive filters and slicers.

KPI performance calculations.



###### **📊 Data Visualization**



The dashboard includes:



KPI Cards

Bar Charts

Line Charts

Donut Charts

Interactive Slicers

Navigation Buttons

Cross-filtering Visuals

Consistent formatting and design principles were applied across all dashboard pages to improve usability and readability.



###### **🚀 Business Value**



The dashboard helps stakeholders:



Monitor sales and order performance.

Track customer activity and geographic distribution.

Identify top-performing product categories.

Evaluate customer satisfaction through review analysis.

Measure delivery efficiency and cancellation trends.

Compare payment method usage and purchasing patterns.



Support operational and strategic business decision-making.



###### **📷 Dashboard Screenshots**



### 1. Overview Dashboard


  `![Overview Dashboard](04_SCREENSHOTS/overview_dashboard.png)

### 2. Customers Dashboard

  '![Customers Dashboard](04_SCREENSHOTS/customers_dashboard.png)



### 3. Products Dashboard

  '![Products Dashboard](04_SCREENSHOTS/products_dashboard.png)



### 4. Sales Dashboard

  '![Sales Dashboard](04_SCREENSHOTS/sales_dashboard.png)



### 5. Analytics Dashboard

  '![Analytics Dashboard](04_SCREENSHOTS/analytics_dashboard.png)



###### **🗂️ Data Model**



**Data Model**



The data model demonstrates relationship design and dimensional modeling skills, which are critical components of Power BI development.



###### **🔍 Key Business Takeaways**



The dashboard provides a comprehensive overview of order volume, customer activity, and payment trends.

Order status analysis helps assess fulfillment performance and cancellation patterns.

Geographic analysis highlights customer concentration across different states and cities.

Product analysis identifies high-performing categories and product characteristics.

Delivery metrics reveal operational efficiency through delivery duration and freight cost patterns.

Interactive filters allow users to explore data from multiple business perspectives.



###### **⚠️ Project Limitations**



The analysis is based on historical Olist e-commerce data rather than live transaction data.

Metrics depend on the definitions, assumptions, and calculations implemented in the Power BI model.

Payment value should not be interpreted as profit because operational costs and business expenses are not included.

The dashboard focuses on descriptive analytics and does not independently determine the causes of business outcomes.



###### **📁 Repository Structure**



Olist-Ecommerce-Analytics-Dashboard/

│

├── Dataset/

├── PowerBI_File/

├── Documentation/

├── 04\_SCREENSHOTS/

│   ├── overview\_dashboard.png

│   ├── customers\_dashboard.png

│   ├── products\_dashboard.png

│   ├── sales\_dashboard.png

│   ├── analytics\_dashboard.png

│   └── data\_model.png

│

└── README.md


###### **🚀Business Insights**


Business Insights and Recommendations


1. Executive Summary
   
The Olist E-commerce Analytics project analyzes Brazilian e-commerce operations to understand sales performance, customer distribution, product performance, payment behavior, order fulfillment, and delivery performance.

Key Performance Indicators (previously recorded; verify against the final Power BI report before publishing):

Total Orders: 99,441
Unique Customers: 96,096
Delivered Orders: 96,478
Total Payment Value: Approximately R$16.01 million
Average Order Value: Approximately R$160.99
Delivery Rate: 97.02%
Cancellation Rate: 0.63%
Average Delivery Time: 12.50 days
Total Products: 32,951
Products with Photos: 32,341
Average Review Score: 4.09 out of 5

2. Sales Performance Insights
   
Finding: The project records 99,441 orders and approximately R$16.01 million in total payment value, with an average order value of approximately R$160.99.

Business implication: These metrics establish a baseline for evaluating sales activity and identifying changes in demand.

Recommendations:
Monitor monthly order volume and payment value.
Identify seasonal trends and peak-demand periods.
Compare order growth with payment-value growth.
Investigate significant changes in sales performance.
Use historical trends to support inventory and operational planning.

4. Customer Distribution Insights
   
Finding: The project identifies 96,096 unique customers across the Brazilian market.

Business implication: Geographic analysis can help identify important customer markets and potential opportunities for customer acquisition.

Recommendations:
Identify states with the highest customer counts.
Compare customer distribution with order volume and payment value.
Investigate geographic markets with relatively low customer activity.
Analyze repeat purchases and customer retention when supported by customer-level order history.


6. Product Performance Insights

   
Finding: The catalog contains 32,951 products, including 32,341 products with photos.

Business implication: Product catalog completeness supports product discovery and analysis, but catalog size alone does not identify the products generating the most revenue.

Recommendations:
Identify top-performing product categories by order volume and payment value.
Compare category performance over time.
Investigate categories with high order volume but relatively low payment value.
Review missing product images and incomplete product information.

8. Delivery Performance Insights

Finding: The previously recorded overall average delivery time is 12.50 days. The updated state-level chart was reported to show:


RR (Roraima): 29.34 days
SP (São Paulo): 8.70 days
The reported difference is 20.64 days.

Business implication: These preliminary figures suggest a potential geographic difference in delivery performance. The underlying calculation and data relationships must be validated before drawing definitive conclusions.

Recommendations:

Validate the delivery-time calculation and confirm that only orders with valid purchase and delivery timestamps are included.
Compare order volumes across customer states.
Investigate shipping routes, seller locations, freight costs, and logistics partners in states with longer delivery times.
Compare delivery performance across all states.
Analyze customer review scores alongside delivery times to investigate potential relationships between delays and customer satisfaction.

9. Order Fulfillment and Cancellation Insights

Finding: Previously recorded results show 96,478 delivered orders, a delivery rate of 97.02%, and a cancellation rate of 0.63%.

Business implication: Order-status analysis helps distinguish completed orders from canceled, unavailable, and in-progress orders.

Recommendations:
Monitor cancellation rates over time.
Investigate cancellation reasons where data is available.
Review unavailable orders for possible inventory or fulfillment issues.
Identify orders remaining in processing or shipping for unusually long periods.
Monitor delayed or unresolved orders.

10. Payment Behavior Insights

Finding: Previously recorded payment-type counts show credit card as the most common payment type, followed by boleto.


Credit card: 76,795
Boleto: 19,784
Voucher: 5,775
Debit card: 1,529
Not defined: 3
These figures may represent payment records rather than unique orders.

Business implication: Payment-method distribution helps describe customer payment preferences. Counts should not be interpreted as unique order counts or payment-value shares without validating the underlying data.

Recommendations:
Compare total payment value across payment methods.
Monitor payment-method trends over time.
Investigate undefined or incomplete payment records.
Analyze installments and payment values where supported by the data.

11. Customer Satisfaction Insights

Finding: The previously recorded average review score is 4.09 out of 5.

Business implication: The average score provides an overall customer feedback indicator but does not identify the causes of positive or negative experiences.

Recommendations:
Compare review scores across product categories.
Investigate low-rated orders and recurring complaint patterns where review comments are available.
Compare review scores across delivery-time groups.
Identify categories with consistently lower ratings.
Use verified customer feedback to prioritize service improvements.

12. Data Quality and Analytical Reliability

Reliable business conclusions depend on correct relationships, consistent metric definitions, valid date calculations, and appropriate aggregation.

Recommendations:
Validate relationships between the datasets.
Confirm that delivery-time calculations exclude orders without valid delivery dates.
Distinguish unique orders from order items and payment records.
Investigate missing values, duplicate records, and inconsistent statuses.
Document the definition and calculation of each KPI.
Reconcile reported metrics with underlying data before publishing final conclusions.

13. Prioritized Business Recommendations

Validate delivery-time calculations and state-level results.
Investigate logistics performance in states with longer delivery times.
Monitor cancellations, unavailable orders, and fulfillment delays.
Analyze customer reviews alongside delivery and product performance.
Use verified sales trends to support demand and resource planning.
Improve product catalog completeness.
Analyze payment behavior using clearly defined metrics.
Maintain data quality and document KPI definitions.

14. Limitations and Further Analysis


The metrics in this section are previously recorded project results and have not all been independently recalculated. In particular, the RR-versus-SP delivery-time comparison requires validation of the DAX calculation, customer-to-order relationship, and order volumes.
Further analysis could include customer retention, repeat purchases, product-category revenue rankings, delivery delays by seller, and the relationship between delivery performance and customer satisfaction. These should be treated as future analysis opportunities until calculated and verified.

Conclusion

The Olist E-commerce Analytics project demonstrates how business intelligence can transform e-commerce data into performance indicators, operational insights, and data-driven recommendations.
By combining sales, customer, product, payment, order-status, and delivery information, the project provides a foundation for understanding business performance and identifying areas for further investigation. Findings should be validated before operational decisions are made.


###### **✅ Conclusion**



This project demonstrates the end-to-end development of a business intelligence solution using Microsoft Power BI. By integrating multiple datasets, creating a structured data model, developing DAX measures, and designing interactive dashboards, the project delivers valuable insights into sales performance, customer behavior, product trends, and delivery operations.



The dashboard provides a scalable foundation for analyzing e-commerce performance and supports informed, data-driven business decision-making.



**⭐ If you found this project useful, consider giving it a star on GitHub.**

(`###### Power BI Report File
The interactive Power BI report was developed using Microsoft Power BI Desktop. Due to file size limitations, the .pbix file is not included in this repository.
This repository contains the project documentation and dashboard screenshots. The Power BI report file is available upon request.)

