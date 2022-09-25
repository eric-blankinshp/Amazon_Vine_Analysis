# Amazon_Vine_Analysis

## Overview
In this project, I had access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I picked one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

## Results

The vine table was filtered to create two new dataFrames for vine and unpaid reviews shown below.

### Vine Reviews

 Total Vine Reviews: 90
 Total 5 Star Reviews: 44
 Percent 5 Star Reviews: 48.89%
 
 
 ### Unpaid Reviews
 
 Total Unpaid Reviews: 37831
 Total 5 Star Reviews: 14704
 Percent 5 Star Reviews: 38.87%
 
 ## Summary

There doesn't seem to be a positivity bias for the reviews. The percentage of five star reviews seems to be larger for unpaid reviews. It would be important to also analyze the one through four star reviews to confirm our theory. Pulling the statistics on the whole range would make sure there isn't a bias between paid and unpaid reviews.
