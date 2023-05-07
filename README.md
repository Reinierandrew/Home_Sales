# Home_Sales
 For this assignment I used an AWS dataset for home_sales to run an SQL query using Spark.
 I ran the query 3 times, the first one on the normal data frame, the second one I cached the data and in the third I used a parquest partition.
 
 The goal was to determine the respective times to produce a query result for each. The results are ijn the following table: 
<img width="403" alt="Screenshot 2023-05-07 at 5 40 29 pm" src="https://user-images.githubusercontent.com/112833174/236664765-b645deb4-b0ef-45e2-b165-0da772767c3b.png">

As you can see the times for the cached and parquet queries were very similar though both significantly faster than querying the uncached data. The dataset used is actually too small to give any insights on the performance differences between caching and parquet partitioniong.
