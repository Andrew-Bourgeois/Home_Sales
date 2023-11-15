# Home_Sales
UNC-CH-DA Module 22 Challenge - Big Data
* Andrew Bourgeois

## **INSTRUCTIONS**
* To run the code clone the repository to your local machine
* Navigate to the /Home_Sales/ folder: Here you will find the Home_Sales_colab.ipynb notebook.
* These Python Spark notebooks were written using Colab, so you will see a button at the top of each will open the notebooks online in Colab. Alternatively you can open them locally, just esnure you have the proper libararies/packages avaialble to import.

## **BACKGROUND**
In this challenge, we used our knowledge of SparkSQL to determine key metrics about home sales data. We then used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verified the table had been uncached.

## **REQUIREMENTS**
1. A Spark DataFrame is created from the dataset. (5 points)

2. A temporary table of the original DataFrame is created. (10 points)

3. A query is written that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year. (5 points)

4. A query is written that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms. (5 points)

5. A query is written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year built rounded to two decimal places. (5 points)

6. A query is written that returns the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.) (10 points)

7. A cache of the temporary "home_sales" table is created and validated. (10 points)

8. The query from step 6 is run on the cached temporary table, and the run time is computed. (10 points)

9. A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read. (10 points)

10. A temporary table of the parquet data is created. (10 points)

11. The query from step 6 is run on the parquet temporary table, and the run time is computed. (10 points)

12. The "home_sales" temporary table is uncached and verified. (10 points)

## **RESOURCES**

* The provided starter code and the class examples from the UNC-CH-DA Module 22.