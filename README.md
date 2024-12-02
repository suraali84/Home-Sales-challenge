# Home-Sales-Big-Data-with-PySpark-SQL

Through utilizing PySpark and Spark SQL on Google Colab, this project serves to determine key metrics about home sales data. Then, Spark is utilized to create temporary views, partition the data, cache and uncache a temporary table. 

As an example, I generated a table with two columns, one of which contained the average price, rounded to 2 decimal places, of only the 4-bedrooms in the database and the other one which contained the grouped years when each property was sold. I also compared the runtimes between running queries on an uncached temporary table, a cached temporary table, and a cached and partitioned with Parquet temporary table.
<br>

##  Key Metric
Some of the data key metric questions that were answered:

- Average price for a four-bedroom house sold for each year;
- Average price of a home for each year it was built that has three bedrooms and three bathrooms;
- Average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet;
- What is the "view" rating for homes costing more than or equal to $350,000;


