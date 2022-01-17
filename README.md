## Amazon Vine Analysis

### Introduction

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. This project aims to analyze Amazon reviews written by members of the paid Amazon Vine program.

### Resources

Datasource:  [Amazon Review Datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)

Software: PostgreSQL 13, pgAdmin 5, AWS, Jupyter Notebook

### Findings:


Total number of Vine reviews and non-Vine reviews for the video games product category
 
  ![Snapshot of reviews](https://github.com/div1085/Amazon_Vine_Analysis/blob/672ec8f4bcfd6c3e4814ca0994e8704a271482c7/Resources/1.png)
  
  
Total number of Vine reviews that were 5 stars and non-Vine reviews were 5 stars?
  
  ![Snapshot of reviews](https://github.com/div1085/Amazon_Vine_Analysis/blob/672ec8f4bcfd6c3e4814ca0994e8704a271482c7/Resources/2.png)
  
  
Total percentage of 5 star Vine review and percentage of 5 star non-Vine reviews
  
  ![Snapshot of reviews](https://github.com/div1085/Amazon_Vine_Analysis/blob/672ec8f4bcfd6c3e4814ca0994e8704a271482c7/Resources/3.png)

### Summary

As per the result there exists a positivity bias for reviews in the Vine program, as vine members overall left 51% of overall positive review, whereas non-vine members left overall 38% of the positive reviews.

Total number of vine users are subset of overall users and respresents only 0.23 % of the overall users (94 out of 40565), which also corelated of positivity bias as the mean of review rating is higher for vine user.
