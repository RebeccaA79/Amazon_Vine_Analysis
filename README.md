# Amazon_Vine_Analysis

## Analysis Overview
The Amazon Vine program was analyzed determine if there is a bias toward favorable reviews from Vine members. This analysis focused on reviews of Pet Products. 

Resources used in the analysis included:
- Amazon Review Dataset for Pet Products: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz
- PySpark
- Google Colab Notebook
- PostgreSQL
- pgAdmin
- AWS RDS


## Results
### Total number of reviews

 - There were 170 Vine reviews
 - There were 37,840 non-Vine reviews

![Vine Reviews](https://github.com/RebeccaA79/Amazon_Vine_Analysis/blob/main/images/vine_reviews.png)

![Non-Vine Reviews](https://github.com/RebeccaA79/Amazon_Vine_Analysis/blob/main/images/non-vine_reviews.png)


### Total number of 5-star reviews

 - There were 65 5-stars Vine reviews
 - There were 20,612 5-stars non-Vine reviews


### Percentage of 5-star reviews

 - 38.24% of Vine reviews were 5-stars
 - 54.47% of non-Vine reviews were 5-stars


## Summary
Based on the results listed above, there does not appear to be a positivity bias of reviews in the Vine Program. There is a larger percentage of 5-star reviews among non-Vine reviews at 54.47% in comparison to 38.24% of 5-star Vine reviews. Since there is a larger number of overall non-Vine reviews, it would be beneficial to run some additional statistical analysis to determine the accuracy of these figures. Running statistics such as median, mean, mode, and standard deviation may provide further clarity. Additionally, R can be leveraged to run different tests such as a T-test.

