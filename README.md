# Amazon_Vine_Analysis

## Overview of the analysis of the Vine program:

In this project we take a look at the Amazon Vine program and tried to determine if there was a bias toward more favorable reviews from Vine members.  In order to do perform this analysis, PySpark was used perform the ETL process by extracting the dataset from a url.  This data was then connected to an AWS RDS instance and loaded and pushed to pgAdmin for data storage and manipulation.  Once the tables were loaded, we downloaded the vine_table to explore the potential for bias in greater detail.  This Vine program analysis was done on video games but the structure of the data is the same so this process will work on any other Vine program.  

## Results:

There is a bulleted list that addresses the three questions for unpaid and paid program reviews (7 pt)

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Summary:

The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)
