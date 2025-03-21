# Home_Sales

Module 22 Challenge


## Overview
Use SparkSQL to determine key metrics about home sales databy using Spark to create temporary views, partition the data, cache and uncache a temporary table. Once the analysis is done, verify that the table has been uncached.


## Results
### Analyzing the Data

1. **What is the average price for a four-bedroom house sold for each year, rounded off to two decimal places?<br>**
   <img src="Tables/1. Avg_4BD.png" />

2. **What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms, rounded off to two decimal places?**<br>
   <img src="Tables/2. Avg_3BD_3BR.png" />

3. **What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet, rounded off to two decimal places?**<br>
   <img src="Tables/3. Avg 3BD_3BR_2FL.png" />

4. **What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off the answer to two decimal places.**<br>
   <img src="Tables/4. GTE_350K_Runtime.png" />

### Further Analysis
**Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.**<br>
      <img src="Tables/5. Runtime_cached.png" />

## Query Times
The cached data took 1.2640 seconds while the parquet table partitioned by date_built took 0.8990SECONDS. 

