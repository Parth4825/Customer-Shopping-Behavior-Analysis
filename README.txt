================================================================================
                CUSTOMER SHOPPING behavior — EDA PROJECT
================================================================================

ABOUT
-----
An exploratory data analysis project on customer shopping behavior. The goal
was to dig into the data and find patterns — who's spending what, how discounts
affect purchases, whether subscribers spend more, and how behavior shifts across
age groups and genders.

The project runs across three tools: Python for cleaning, MySQL for querying,
and Power BI for visualizing the findings.


FILES
-----
  customer_shopping_behavior.csv     →. CSV file with Customer Shopping Behavior data
  Customer_Shopping_behavior.ipynb  →  data cleaning and prep (Python/Pandas)
  customer_behavior.sql              →  10 exploratory SQL queries
  Customer_behavior.pbix            →  Power BI dashboard


WHAT WAS DONE
-------------
The raw data was cleaned in Pandas — handled missing review ratings, standardized
column names, dropped a duplicate column, and created two new features: age_group
and purchase_frequency_days to make the analysis more meaningful.

The cleaned data was then pushed to a local MySQL database using SQLAlchemy,
where 10 business questions were explored — things like revenue by gender,
top-rated products, subscriber vs. non-subscriber spending, customer segmentation,
and age group revenue contribution.

Everything was then brought together in a Power BI dashboard for visual storytelling.


HOW TO RUN
----------
  1. pip install pandas numpy matplotlib sqlalchemy pymysql
  2. Update the CSV file path in the notebook and run all cells
  3. Open customer_behavior.sql in MySQL Workbench (database: pandasdb)
  4. Open the .pbix file in Power BI Desktop and refresh the data source


================================================================================
