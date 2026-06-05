## 🛒 **Olist Brazilian E-Commerce Analytics Dashboard**



An End-to-End Data Analytics Project using PostgreSQL, Excel, Power BI, Power Query, DirectQuery and DAX



A professional, interactive Power BI dashboard built to analyze Brazilian e-commerce marketplace performance using the Olist dataset.



This project is an end-to-end data analytics and business intelligence solution where the complete workflow includes dataset collection, Excel-based data understanding, PostgreSQL database creation, SQL table and column setup, data import, Power Query cleaning, data modeling, DAX measures, DirectQuery connection, and Power BI dashboard development.



The dashboard helps analyze revenue performance, order trends, customer behavior, product categories, delivery performance, customer reviews, payment patterns, seller performance, and regional business insights.



![image alt](https://github.com/Ashmit-299/Olist-Brazilian-Ecommerce-Analytics-Dashboard/blob/5688b9e3498c26d439c5a9ef9c8f7ed1b3adb455/images/Combined%20Olist%20Dashboard.png)





###### 📌 **Short Description / Purpose**



The **Olist Brazilian E-Commerce Analytics Dashboard** is a Power BI business intelligence project created to understand the performance of a Brazilian e-commerce marketplace.



The main purpose of this project is to convert raw e-commerce data into meaningful business insights using a complete data analytics workflow.



Unlike a basic static dashboard, this project uses \*\*PostgreSQL as the database source\*\* and \*\*Power BI DirectQuery\*\* to connect with the database. This makes the project more realistic because the dashboard is connected to a database instead of only using fixed imported Excel or CSV files.



The project covers:



\- Data understanding using Excel

\- Database creation using PostgreSQL

\- Table and column creation

\- Importing large dataset files into SQL tables

\- Data cleaning using Power Query Editor

\- Data modeling in Power BI

\- DAX measure creation

\- Dashboard design

\- Business insights and recommendations





###### 👥 **Intended Users**



This dashboard is designed for:



\- E-Commerce Business Managers

\- Data Analysts

\- Business Intelligence Analysts

\- Operations Teams

\- Logistics Managers

\- Product and Category Managers

\- Seller Performance Teams

\- Customer Experience Teams

\- Business Strategy Teams

\- Data Analytics Portfolio Reviewers

\- Recruiters and Hiring Managers





###### 🛠️ **Tech Stack**



The project was built using the following tools and technologies:



📊 **Power BI Desktop**



Used for:



\- Dashboard development

\- Data modeling

\- DirectQuery connection

\- Report page creation

\- Visual design

\- KPI cards

\- Charts and graphs

\- Maps

\- Matrix tables

\- Slicers and filters

\- Drill-through page

\- Navigation structure



🗄️ **PostgreSQL**



Used as the main database system for storing and managing the Olist dataset.



PostgreSQL was used for:



\- Creating a new database

\- Creating tables

\- Defining columns

\- Setting data types

\- Importing large dataset files

\- Managing relational data

\- Connecting database tables with Power BI



🧾 **SQL**



Used for:



\- Creating database schema

\- Creating tables

\- Defining column names and data types

\- Importing data into tables

\- Checking data quality

\- Validating row counts

\- Understanding table relationships

\- Preparing data for Power BI reporting



📂 **Excel**



Used for:



\- Opening the dataset files

\- Understanding column names

\- Checking sample records

\- Reviewing data structure

\- Identifying data types

\- Understanding how each table is connected

\- Planning PostgreSQL table creation



Excel was mainly used for initial data understanding before creating the tables in PostgreSQL.



🧹 **Power Query Editor**



Used for:



\- Data cleaning

\- Changing data types

\- Removing unnecessary columns

\- Formatting date fields

\- Renaming columns

\- Transforming data

\- Preparing data for reporting

\- Creating clean fields for dashboard visuals



🧠 **DAX**



Used for creating business KPIs and calculations such as:



\- Total Revenue

\- Total Orders

\- Total Customers

\- Average Order Value

\- Average Rating

\- On-Time Orders

\- Late Orders

\- On-Time Delivery %

\- Positive Review %

\- Negative Review %

\- Revenue per Seller

\- Year-over-Year %

\- Rolling 30 Days Revenue

\- Revenue Year-to-Date



🔄 **DirectQuery**



Used to connect Power BI directly with PostgreSQL.



DirectQuery was used because the dataset contains large files and multiple related tables. Instead of importing all data into Power BI, the report connects to the PostgreSQL database and fetches data from the database source.



🌐 **GitHub**



Used for:



\- Project documentation

\- Portfolio presentation

\- Uploading Power BI template file

\- Uploading screenshots

\- Uploading SQL scripts

\- Explaining the complete project workflow





###### 📂 **Data Source**



\# Dataset Used



**Brazilian E-Commerce Public Dataset by Olist**



The dataset was downloaded from Kaggle. It contains real-world e-commerce marketplace data from Brazil.



The dataset includes information about:



\- Orders

\- Customers

\- Sellers

\- Products

\- Product categories

\- Payments

\- Reviews

\- Delivery dates

\- Customer locations

\- Seller locations

\- Geolocation data





📌 **Dataset Details**



\- \*\*Source Platform:\*\* Kaggle

\- \*\*Dataset Name:\*\* Brazilian E-Commerce Public Dataset by Olist

\- \*\*Business Domain:\*\* E-Commerce / Online Marketplace

\- \*\*Country:\*\* Brazil

\- \*\*Data Type:\*\* Transactional relational dataset

\- \*\*Files Used:\*\* Multiple CSV files from the Olist dataset

\- \*\*Approximate Data Size:\*\* 10 lakh+ records across multiple files

\- \*\*Database Used:\*\* PostgreSQL

\- \*\*Power BI Connection Mode:\*\* DirectQuery



\---



📁 **Main Dataset Files**



The dataset contains multiple related CSV files. The main files used in this project include:



\- `olist\_orders\_dataset.csv`

\- `olist\_order\_items\_dataset.csv`

\- `olist\_order\_payments\_dataset.csv`

\- `olist\_order\_reviews\_dataset.csv`

\- `olist\_customers\_dataset.csv`

\- `olist\_sellers\_dataset.csv`

\- `olist\_products\_dataset.csv`

\- `olist\_geolocation\_dataset.csv`

\- `product\_category\_name\_translation.csv`



These files were first reviewed in Excel to understand the columns, data structure, and relationship between tables. After reviewing the files, PostgreSQL tables were created and the data was imported into the database.





🔄 **Complete Project Workflow**



This project followed a complete end-to-end data analytics workflow.





1\. Dataset Download from Kaggle



The Olist Brazilian E-Commerce dataset was downloaded from Kaggle.



The dataset was available in multiple CSV files. Each file represented a different business entity such as customers, orders, sellers, products, payments, reviews, and geolocation.





2\. Dataset Understanding using Excel



Before creating the database, each CSV file was opened and reviewed in Excel.



Excel was used to understand:



\- Number of columns in each file

\- Column names

\- Sample records

\- Data format

\- Date columns

\- Numeric columns

\- Text columns

\- Primary key columns

\- Foreign key columns

\- Relationship between files



This step was important because the PostgreSQL table structure had to be created manually based on the columns available in the dataset.





3\. PostgreSQL Database Creation



After understanding the dataset structure, a new PostgreSQL database was created for the project.



The database was created to store all Olist dataset tables in a structured format.



Example database name:



```sql

CREATE DATABASE olist\_db;



The PostgreSQL database acted as the main source system for the Power BI report.





4\. SQL Table Creation



After creating the database, separate tables were created for each Olist dataset file.



Each table was created by defining proper column names and data types based on the CSV files.



Example tables created:



CREATE TABLE customers (

&#x20;   customer\_id VARCHAR(100),

&#x20;   customer\_unique\_id VARCHAR(100),

&#x20;   customer\_zip\_code\_prefix INT,

&#x20;   customer\_city VARCHAR(100),

&#x20;   customer\_state VARCHAR(10)

);

CREATE TABLE orders (

&#x20;   order\_id VARCHAR(100),

&#x20;   customer\_id VARCHAR(100),

&#x20;   order\_status VARCHAR(50),

&#x20;   order\_purchase\_timestamp TIMESTAMP,

&#x20;   order\_approved\_at TIMESTAMP,

&#x20;   order\_delivered\_carrier\_date TIMESTAMP,

&#x20;   order\_delivered\_customer\_date TIMESTAMP,

&#x20;   order\_estimated\_delivery\_date TIMESTAMP

);

CREATE TABLE order\_items (

&#x20;   order\_id VARCHAR(100),

&#x20;   order\_item\_id INT,

&#x20;   product\_id VARCHAR(100),

&#x20;   seller\_id VARCHAR(100),

&#x20;   shipping\_limit\_date TIMESTAMP,

&#x20;   price NUMERIC,

&#x20;   freight\_value NUMERIC

);

CREATE TABLE order\_payments (

&#x20;   order\_id VARCHAR(100),

&#x20;   payment\_sequential INT,

&#x20;   payment\_type VARCHAR(50),

&#x20;   payment\_installments INT,

&#x20;   payment\_value NUMERIC

);

CREATE TABLE order\_reviews (

&#x20;   review\_id VARCHAR(100),

&#x20;   order\_id VARCHAR(100),

&#x20;   review\_score INT,

&#x20;   review\_comment\_title TEXT,

&#x20;   review\_comment\_message TEXT,

&#x20;   review\_creation\_date TIMESTAMP,

&#x20;   review\_answer\_timestamp TIMESTAMP

);

CREATE TABLE products (

&#x20;   product\_id VARCHAR(100),

&#x20;   product\_category\_name VARCHAR(100),

&#x20;   product\_name\_length NUMERIC,

&#x20;   product\_description\_length NUMERIC,

&#x20;   product\_photos\_qty NUMERIC,

&#x20;   product\_weight\_g NUMERIC,

&#x20;   product\_length\_cm NUMERIC,

&#x20;   product\_height\_cm NUMERIC,

&#x20;   product\_width\_cm NUMERIC

);

CREATE TABLE sellers (

&#x20;   seller\_id VARCHAR(100),

&#x20;   seller\_zip\_code\_prefix INT,

&#x20;   seller\_city VARCHAR(100),

&#x20;   seller\_state VARCHAR(10)

);

CREATE TABLE geolocation (

&#x20;   geolocation\_zip\_code\_prefix INT,

&#x20;   geolocation\_lat NUMERIC,

&#x20;   geolocation\_lng NUMERIC,

&#x20;   geolocation\_city VARCHAR(100),

&#x20;   geolocation\_state VARCHAR(10)

);

CREATE TABLE product\_category\_translation (

&#x20;   product\_category\_name VARCHAR(100),

&#x20;   product\_category\_name\_english VARCHAR(100)

);





5\. Data Import into PostgreSQL



After creating the tables, the CSV files were imported into PostgreSQL.



The data import process included:



Selecting the correct table

Mapping columns correctly

Checking data types

Handling date columns

Importing large files

Validating row count after import



Example import approach:



COPY customers

FROM 'file\_path/olist\_customers\_dataset.csv'

DELIMITER ','

CSV HEADER;



For local system import, PostgreSQL \\copy can also be used through psql:



\\copy customers FROM 'file\_path/olist\_customers\_dataset.csv' DELIMITER ',' CSV HEADER;



This step was one of the most important parts of the project because all raw data was moved from CSV files into a proper relational database.





6\. Table Relationship Understanding



After importing the data, the relationship between tables was analyzed.



Main relationships used:



Customers table connects with Orders table using customer\_id

Orders table connects with Order Items using order\_id

Orders table connects with Payments using order\_id

Orders table connects with Reviews using order\_id

Order Items table connects with Products using product\_id

Order Items table connects with Sellers using seller\_id

Products table connects with Category Translation using product\_category\_name

Customers and Sellers connect with location fields using city/state/zip code information



This relationship structure helped build a proper reporting model in Power BI.





7\. Power BI Connection with PostgreSQL



After the database setup was completed, PostgreSQL was connected with Power BI Desktop.



Connection steps:



Open Power BI Desktop.

Select Get Data.

Choose PostgreSQL database.

Enter server name and database name.

Select DirectQuery mode.

Select required tables.

Load the tables into Power BI model.



The report was built using DirectQuery, meaning Power BI connects directly to the PostgreSQL database instead of storing all data inside the Power BI file.





8\. Power Query Cleaning and Transformation



After connecting the data to Power BI, the data was cleaned using Power Query Editor.



Cleaning steps included:



Changing incorrect data types

Formatting date and time columns

Removing unnecessary fields

Renaming columns for readability

Handling null values

Creating clean category names

Preparing delivery date columns

Preparing review score fields

Preparing payment fields

Checking duplicate or missing values

Creating helper columns where needed



Power Query was used to make the data clean and ready for dashboard development.





9\. Data Modeling in Power BI



After cleaning the data, relationships were created in Power BI Model View.



The model connected multiple Olist tables such as:



Customers

Orders

Order Items

Products

Sellers

Payments

Reviews

Category Translation

Geolocation



The model was designed to support:



Revenue analysis

Order analysis

Category analysis

Customer geography analysis

Seller performance analysis

Review analysis

Payment analysis

Delivery analysis





10\. DAX Measure Creation



DAX measures were created to calculate business KPIs and dashboard metrics.



Some of the major KPIs created:



Total Revenue

Total Orders

Total Customers

Average Order Value

Total Sellers

Revenue Per Seller

Average Rating

Positive Review %

Negative Review %

Late Orders

On-Time Orders

On-Time Delivery %

Revenue Year-to-Date

Rolling 30 Days Revenue

Year-over-Year Growth %





11\. Dashboard Development in Power BI



After data modeling and DAX measure creation, multiple Power BI report pages were created.



The dashboard contains multiple visuals such as:



KPI cards

Line charts

Bar charts

Donut charts

Maps

Matrix tables

Category comparison visuals

Payment analysis visuals

Review analysis visuals

Seller performance visuals

Drill-through detail page



The dashboard was designed to analyze both high-level business performance and detailed operational performance.





###### 🧱 **Data Model**



The dashboard uses a relational data model based on the Olist dataset.



Main Tables

Orders Table



Contains order-level information such as:



Order ID

Customer ID

Order status

Purchase timestamp

Approved date

Delivered carrier date

Delivered customer date

Estimated delivery date

Customers Table



Contains customer-related information such as:



Customer ID

Customer unique ID

Customer city

Customer state

Customer zip code

Order Items Table



Contains item-level transaction details such as:



Order ID

Product ID

Seller ID

Price

Freight value

Shipping limit date

Products Table



Contains product-related details such as:



Product ID

Product category

Product weight

Product dimensions

Product photo quantity

Payments Table



Contains payment-related information such as:



Order ID

Payment type

Payment installments

Payment value

Reviews Table



Contains customer review information such as:



Review ID

Order ID

Review score

Review creation date

Review answer timestamp

Sellers Table



Contains seller information such as:



Seller ID

Seller city

Seller state

Seller zip code

Geolocation Table



Contains geographical information such as:



Zip code prefix

Latitude

Longitude

City

State

Category Translation Table



Contains translated product category names from Portuguese to English.





###### ❓ **Business Problem**



An e-commerce marketplace needs to understand how its business is performing across revenue, orders, customers, sellers, payments, reviews, and delivery operations.



The business faces several important questions:



Which product categories generate the highest revenue?

Which states and cities contribute the most revenue?

Which sellers are generating the most business?

Are customers receiving orders on time?

Which categories face delivery delays?

How does late delivery affect customer ratings?

Which payment methods are used the most?

What is the average order value?

Which categories have strong revenue but weak ratings?

Which regions need better delivery performance?



Business leaders need a single interactive dashboard to monitor these questions and take better decisions.





###### 🎯 **Goal of the Dashboard**



The goal of this dashboard is to provide a complete business intelligence solution for e-commerce analysis.



The dashboard helps stakeholders:



Track revenue, orders, customers, sellers, and AOV.

Monitor monthly and yearly business trends.

Analyze product category performance.

Understand customer geography and regional demand.

Track delivery performance and late orders.

Analyze customer reviews and satisfaction.

Understand payment method contribution.

Evaluate seller performance.

Identify business risks and improvement areas.

Make data-driven business decisions.





###### 🔄 **DirectQuery and Live Database Connection**



This project uses Power BI DirectQuery mode connected with a PostgreSQL database.



This means the dashboard is connected directly to the database source instead of only using imported static data.



Why DirectQuery Was Used



DirectQuery was used because:



The dataset contains large files.

Multiple tables were used.

Data was stored in PostgreSQL.

Power BI needed to connect directly with the database.

The project needed to show a real-world database reporting workflow.

Benefits of DirectQuery

Works better with large datasets.

Keeps the dashboard connected to the database.

Reduces Power BI file size.

Makes the project more industry-oriented.

Allows database-level data management.

Helps demonstrate SQL + Power BI integration.

Important Note



The uploaded .pbit file contains the report structure, model, visuals, measures, and connection setup.



Users opening the .pbit file may need to configure their own PostgreSQL database connection and credentials.





###### 📊 **Dashboard Pages**



The Power BI report contains the following pages:



1\. Executive Overview



2\. Revenue Performance



3\. Category Analysis



4\. Customer Geography



5\. Delivery Performance



6\. Customer Reviews



7\. Payment Analysis



8\. Seller Performance



9\. Category Detail / Drill-through Page



If your final report contains only 8 pages, remove the 9th page from this list.



###### 📌 **Dashboard Features / Highlights**


1\. Executive Overview



The Executive Overview page provides a high-level summary of the complete e-commerce business.



Key Metrics

Total Revenue

Total Orders

Total Customers

Average Order Value

On-Time Delivery %

Average Rating

YoY %

Key Visuals

Orders by year-month

Revenue trend

Top 10 categories by revenue

Revenue by city

Order status share

Business Purpose



This page helps users quickly understand the overall performance of the e-commerce marketplace.


2\. Revenue Performance



The Revenue Performance page focuses on revenue growth and time-based performance.



Key Metrics

Revenue vs Last Year

Rolling 30 Days Revenue

Revenue Year-to-Date

Revenue by Category and Year

Orders by Year

AOV by Year

Key Visuals

Revenue vs last year line chart

Rolling 30 days revenue visual

Revenue YTD trend

Category x year matrix

Business Purpose



This page helps analyze how revenue is changing over time and which categories contribute most to yearly performance.


3\. Category Analysis



The Category Analysis page focuses on product category performance.



Key Metrics

Category Revenue

Category Orders

Average Order Value

Average Rating

On-Time Delivery %

Key Visuals

Category revenue share

AOV vs orders by category

Top 10 categories by rating

Top 20 category performance table

Business Purpose



This page helps identify high-revenue categories, high-AOV categories, and categories with better or weaker customer ratings.


4\. Customer Geography



The Customer Geography page analyzes regional customer demand.



Key Metrics

Revenue by customer state

Revenue by customer city

Orders by state

AOV by state

Category performance by state

Key Visuals

Revenue by customer state map

Top 10 customer states by revenue

Top 10 customer cities by revenue

Customer state x category matrix

Business Purpose



This page helps understand which Brazilian states and cities generate the highest business contribution.


5\. Delivery Performance



The Delivery Performance page focuses on order fulfillment and logistics efficiency.



Key Metrics

Late Orders

On-Time Delivery %

Average Delivery Days

Late % by State

Order Status by Category

Key Visuals

Late orders by year-month

Average delivery days by category

Late % by customer states

Order status by category

Business Purpose



This page helps identify logistics delays, late delivery patterns, and regions/categories that need operational improvement.


6\. Customer Reviews



The Customer Reviews page focuses on customer satisfaction and rating behavior.



Key Metrics

Positive Review %

Negative Review %

Average Rating

Rating Distribution

Average Rating by Category

Average Rating: Late vs On-Time Orders

Key Visuals

Rating distribution chart

Average rating by category

Average rating late vs on-time

Positive and negative review KPI cards

Business Purpose



This page helps understand customer feedback and shows how delivery performance affects customer ratings.





7\. Payment Analysis



The Payment Analysis page focuses on customer payment behavior.



Key Metrics

Payment Value

Payment Type Share

Average Installments

Orders by Payment Type

AOV by Payment Type

Key Visuals

Payment type share chart

Average installments by payment type

Payment value trend

Payment summary table

Business Purpose



This page helps understand which payment methods are most used and how payment behavior affects order value.





8\. Seller Performance



The Seller Performance page analyzes seller contribution and seller geography.



Key Metrics

Total Sellers

Revenue Per Seller

Top Sellers by Revenue

Revenue by Seller State

Seller State x Category Performance

Key Visuals

Top 10 sellers by revenue

Revenue by seller state map

Seller state x category matrix

Seller performance KPI cards

Business Purpose



This page helps identify top sellers, seller concentration, and regional seller contribution.





9\. Category Detail / Drill-through Page



The Category Detail page provides a deep-dive view of a selected product category.



Key Metrics

Selected Category Revenue

Category Orders

Category AOV

On-Time Delivery %

Average Rating

Key Visuals

Category revenue trend

Top customer states by revenue

Category KPI cards

Category detail table

Business Purpose



This page helps users drill through from a selected category and analyze its detailed performance.



###### 🧭 **Navigation and User Experience**



The dashboard can be improved using a left-side navigation panel.



Navigation Pages

Overview

Revenue

Category

Customer Geography

Delivery

Reviews

Payments

Sellers

Category Detail

Navigation Benefits

Easy movement between report pages

Professional dashboard experience

Better user flow

Clean report structure

Useful for portfolio presentation

Similar to real business dashboards



###### 💼 **Business Impact**



The dashboard can help business teams in the following ways:



1\. Revenue Growth Analysis



Helps identify high-revenue categories, months, cities, and sellers.



2\. Customer Experience Improvement



Shows the connection between delivery performance and customer reviews.



3\. Delivery Optimization



Highlights late order patterns by month, state, and category.



4\. Seller Performance Monitoring



Helps identify top sellers and regional seller concentration.



5\. Product Category Strategy



Supports decisions around high-performing, low-performing, and premium categories.



6\. Payment Behavior Understanding



Shows payment method preference and payment value distribution.



7\. Regional Business Strategy



Helps understand which states and cities generate the most revenue.



8\. Operational Risk Reduction



Identifies late delivery areas and categories with weaker fulfillment performance.



###### 🧮 **Key DAX Measures**



Some of the important DAX measures used in the dashboard include:



Total Revenue = SUM(order\_items\[price]) + SUM(order\_items\[freight\_value])

Total Orders = DISTINCTCOUNT(orders\[order\_id])

Total Customers = DISTINCTCOUNT(customers\[customer\_id])

Total Sellers = DISTINCTCOUNT(sellers\[seller\_id])

Average Order Value = DIVIDE(\[Total Revenue], \[Total Orders], 0)

Average Rating = AVERAGE(order\_reviews\[review\_score])



Note: Table and column names may differ depending on the final Power BI model. Update table names according to your actual model.



###### 📷 **Screenshots / Dashboard Preview**



1\. Executive Overview

![image alt](https://github.com/Ashmit-299/Olist-Brazilian-Ecommerce-Analytics-Dashboard/blob/419d74ed975015945e4bb89befa474ad7b11702e/images/Overview(Executive%20Dashboard).png)



2\. Revenue Performance

![image alt](https://github.com/Ashmit-299/Olist-Brazilian-Ecommerce-Analytics-Dashboard/blob/419d74ed975015945e4bb89befa474ad7b11702e/images/Sales%20Trend.png)



3\. Category Analysis

![image alt](https://github.com/Ashmit-299/Olist-Brazilian-Ecommerce-Analytics-Dashboard/blob/419d74ed975015945e4bb89befa474ad7b11702e/images/Category%20%26%20Product.png)



4\. Customer Geography

![image alt](https://github.com/Ashmit-299/Olist-Brazilian-Ecommerce-Analytics-Dashboard/blob/419d74ed975015945e4bb89befa474ad7b11702e/images/Customer_Geo.png)



5\. Delivery Performance

![image alt](https://github.com/Ashmit-299/Olist-Brazilian-Ecommerce-Analytics-Dashboard/blob/419d74ed975015945e4bb89befa474ad7b11702e/images/Delivery%20%26%20Logistics.png)



6\. Customer Reviews

![image alt](https://github.com/Ashmit-299/Olist-Brazilian-Ecommerce-Analytics-Dashboard/blob/419d74ed975015945e4bb89befa474ad7b11702e/images/Reviews.png)



7\. Payment Analysis

![image alt](https://github.com/Ashmit-299/Olist-Brazilian-Ecommerce-Analytics-Dashboard/blob/419d74ed975015945e4bb89befa474ad7b11702e/images/Payments%20Details.png)



8\. Seller Performance

![image alt](https://github.com/Ashmit-299/Olist-Brazilian-Ecommerce-Analytics-Dashboard/blob/419d74ed975015945e4bb89befa474ad7b11702e/images/Seller.png)



9\. Category Detail / Drill-through

![image alt](https://github.com/Ashmit-299/Olist-Brazilian-Ecommerce-Analytics-Dashboard/blob/419d74ed975015945e4bb89befa474ad7b11702e/images/Drillthrough.png)



###### 📁 **Project Structure**



Olist-Brazilian-Ecommerce-Analytics-Dashboard/



│

├── README.md

│

├── dashboard/

│   └── ECommerce\_Olist.pbit

│

├── data/

│   └── dataset\_source.txt

│

├── images/

│   ├── executive\_overview.png

│   ├── revenue\_performance.png

│   ├── category\_analysis.png

│   ├── customer\_geography.png

│   ├── delivery\_performance.png

│   ├── customer\_reviews.png

│   ├── payment\_analysis.png

│   ├── seller\_performance.png

│   └── category\_detail.png

│

├── docs/

│   └── data\_model.png

│

└── assets/

&#x20;   └── icons/



###### 🚀 **How to Use**



Download the .pbit file from the dashboard/ folder.

Download the Olist Brazilian E-Commerce dataset from Kaggle.

Open the CSV files in Excel to understand the columns and structure.

Create a new PostgreSQL database.

Create tables in PostgreSQL according to the dataset columns.

Import the CSV files into the PostgreSQL tables.

Open the Power BI template file in Power BI Desktop.

Configure the PostgreSQL database connection.

Load the report using DirectQuery.

Use slicers and filters to analyze revenue, orders, customers, categories, sellers, delivery, reviews, and payments.

Navigate between report pages using the dashboard pages.

Use the drill-through page for detailed category analysis.



###### 📌 **Project Outcome**



This project demonstrates the ability to build a complete end-to-end data analytics solution using Excel, PostgreSQL, SQL, Power BI, Power Query, DirectQuery, and DAX.



The project shows practical skills in:



Dataset understanding

Database creation

Table creation

Data import

Data cleaning

Data modeling

KPI calculation

Dashboard development

Business analysis

Data storytelling

GitHub documentation



The dashboard helps stakeholders monitor e-commerce marketplace performance, identify operational problems, analyze customer and seller behavior, and make data-driven decisions.



###### 👤 **Author**

Ashmit Pandey
GitHub: https://github.com/Ashmit-299
LinkedIn: www.linkedin.com/in/ashmit-pandey-269675357
Email: pandeyashmit299@gmail.com

