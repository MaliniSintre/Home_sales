# Home_sales
Module 22 Challenge

1. Import the necessary PySpark SQL functions for this assignment.
2. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame
3. Create a temporary table called home_sales.
4. Answer the following questions using SparkSQL:
      - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
      - 
+----------+---------+
|year_built|avg_price|
+----------+---------+
|2010      |292859.62|
|2011      |291117.47|
|2012      |293683.19|
|2013      |295962.27|
|2014      |290852.27|
|2015      |288770.3 |
|2016      |290555.07|
|2017      |292676.79|
+----------+---------+
      - What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
      - What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
      - What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000?Determine the run time for this query, and round off your answer to two decimal places.
      - Cache your temporary table home_sales.
      - Check if your temporary table is cached.
      - Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
      - Partition by the "date_built" field on the formatted parquet home sales data.
      - Create a temporary table for the parquet data.
      - Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
      - Uncache the home_sales temporary table.
      - Verify that the home_sales temporary table is uncached using PySpark.
5. Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.
