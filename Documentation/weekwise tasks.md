**Week 1 – Data Understanding, Loading, and Cleaning in Power BI**

During the first week, the primary focus was on understanding raw data and preparing it for analysis using Power BI. We worked on a real-world dataset related to U.S. natural disasters obtained from FEMA.

The process began with importing the dataset into Power BI and understanding its structure, columns, and data types. We explored the importance of data quality and how unclean data can negatively impact analysis and decision-making.

Key Activities Performed:

Loading datasets into Power BI

Identifying incorrect or inconsistent values

Handling missing (null) values

Removing duplicate records

Deleting unnecessary columns

Renaming columns for better clarity

Changing data types where required

This week emphasized that data cleaning is one of the most critical steps in analytics. Without structured and reliable data, dashboards and insights can be misleading.

**Week 2 – Data Cleaning and Exploratory Data Analysis Using Python**

In the second week, we shifted from Power BI to Python and used Jupyter Notebook for programmatic data analysis. This week focused on preprocessing and exploring datasets using Python libraries.

We worked with the Netflix dataset to perform Exploratory Data Analysis (EDA), which helped in identifying trends, distributions, and patterns before visualization.

Tools and Libraries Used:

Pandas (for data manipulation)

NumPy (for numerical operations)

Matplotlib & Seaborn (for visualization)

Key Learning Outcomes:

Handling missing data using Python

Filtering and grouping datasets

Performing aggregation operations

Identifying outliers and trends

Understanding distributions of categorical and numerical data

This week built a strong foundation in analytical thinking and helped in understanding data behavior before moving into dashboard creation.

**Week 3 – Live Data Concepts and API Fundamentals**

Week three introduced the concept of live or real-time data. Unlike static datasets, live data continuously updates and reflects real-world changes instantly.

We learned how APIs (Application Programming Interfaces) function as bridges between data servers and applications like Power BI.

Major Concepts Covered:

Difference between static and live data

API structure and response format (JSON)

How data is requested and received from servers

Importance of authentication in APIs

Data refresh mechanisms in dashboards

This week helped in understanding how businesses rely on dynamic dashboards that reflect updated data automatically.

**Week 4 – Live Data Integration, CRM Concepts, and ETL Pipeline**

In the fourth week, we explored live data integration in more detail. We learned how to connect Power BI to web-based data sources and APIs.

We also discussed Customer Relationship Management (CRM) systems and their importance in managing customer interactions and service processes.

One of the platforms introduced was Zendesk, a cloud-based customer service solution widely used for ticket management and customer support operations.

ETL Pipeline

We also studied the ETL process:

Extract – Collecting data from multiple sources

Transform – Cleaning and modifying data into a usable format

Load – Storing processed data into a system for reporting

Understanding ETL gave insights into how real-world organizations manage large-scale data workflows before analysis.

**Week 5 – Visualizations and Data Modeling in Power BI**

Week five focused on transforming structured data into meaningful visual insights. We learned that effective dashboards require not only good design but also a strong data model.

Understanding Dataset Types

Numerical Data – Sales, revenue, profit, quantity

Categorical Data – Region, product category, department

Time-Based Data – Dates, months, quarters, years

Choosing the right visualization depends heavily on the type of data involved.

Types of Visualizations Learned
Bar Chart

Used for comparing values across categories.

Pie Chart

Represents proportions of a whole (best for limited categories).

Line Chart

Used for time-series analysis to track trends over periods.

Data Modeling Concepts

We studied how tables are connected using:

Primary Key – Unique identifier

Foreign Key – Connects tables

Types of Relationships:

One-to-One (1:1)

One-to-Many (1:M)

Many-to-One (M:1)

Many-to-Many (M:M)

Fact and Dimension Tables

Fact Table – Contains measurable data (sales, profit)

Dimension Table – Contains descriptive data (customer, product)

Star Schema

The Star Schema structure places the fact table at the center with dimension tables connected around it.

Benefits:

Improved performance

Simplified relationships

Accurate aggregations

Week 5 highlighted that strong data modeling ensures reliable dashboard insights.

**Week 6 – DAX and Advanced Calculations in Power BI**

Week six introduced Data Analysis Expressions (DAX), which allows advanced and dynamic calculations inside Power BI.

Introduction to DAX

DAX is a formula language used to create:

Measures

Calculated columns

Calculated tables

Unlike Excel formulas, DAX works on the entire data model and responds dynamically to filters.

Creating Measures

We started with basic aggregation functions:

SUM()

COUNT()

AVERAGE()

Example:
Total Sales = SUM(Sales[Amount])

Explicit vs Implicit Measures

Implicit Measures – Auto-created by Power BI

Explicit Measures – Manually written using DAX

Explicit measures are more professional, reusable, and optimized.

Understanding Context

Filter Context – Filters applied through visuals or slicers

Row Context – Row-by-row calculations

Understanding context is crucial for correct DAX results.

CALCULATE Function

CALCULATE() modifies filter context and applies logic-based conditions inside measures.

Structure:
CALCULATE(Expression, Filter1, Filter2, ...)

It is considered the most important function in DAX.

Conditional Logic

We practiced:

IF()

Nested IF conditions

Used for classification, performance indicators, and threshold-based metrics.

Time Intelligence (Overview)

We were introduced to:

Year-to-Date (YTD)

Month-over-Month (MoM)

Year-over-Year (YoY)

These functions enable powerful time-based comparisons.
