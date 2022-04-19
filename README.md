# Amazon_Vine_Analysis

## Overview of the analysis
This project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. This project will sepecifically analyze digital video game products by using Pyspark at first to conduct the ETL process and then analyze reviews to see whether there is any bias toward favorable reviews from Vine members.

## Results:

In order to maintain the value of reviews, I filter out reviews whose helpful vote rates are less than 50% and total votes are less than 20. These are analysis results:
![no paid](https://github.com/ZiwenLyu/Amazon_Vine_Analysis/blob/main/vine_nopaid.png)
![paid](https://github.com/ZiwenLyu/Amazon_Vine_Analysis/blob/main/vine_paid.png)

- From two graphs we can see that, there are 1685 reviews from non-vine-program members, and 0 reviews from vine-program members.
- 5 star reviews from non-vine-program members are 631. 5 star reviews from vine-program members are 0.
- 5 star review percentage of non-vine-program members are 37.4%


## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
