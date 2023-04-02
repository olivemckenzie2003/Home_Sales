Code developed in DataBricks
download home_sales_revised.csv

url = "https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv"

Home_Sales.ipynb

# Home_Sales

The time taken for run the query 6 is 0.69 seconds
6. A query is written that returns the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.) 


The time taken to run query 8 is 0.38 secounds 
8.The query from step 6 is run on the cached temporary table, and the run time is computed. 


The time taken to run query 11 is 1.049 secounds 
11. The query from step 6 is run on the parquet temporary table, and the run time is computed. 




Requirements for assignment 22


1. A Spark DataFrame is created from the dataset. 

2. A temporary table of the original DataFrame is created. 

3. A query is written that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year.

4. A query is written that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms.

5. A query is written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year built rounded to two decimal places. 

6. A query is written that returns the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.) 

7. A cache of the temporary "home_sales" table is created and validated. 

8. The query from step 6 is run on the cached temporary table, and the run time is computed. 

9. A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read.

10. A temporary table of the parquet data is created. 

11. The query from step 6 is run on the parquet temporary table, and the run time is computed. 

12. The "home_sales" temporary table is uncached and verified. 



