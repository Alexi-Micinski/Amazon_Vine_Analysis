# Amazon Vine Review Analysis

## Overview of the analysis:

Amazon Vine is a program that helps companies receive reviews from Vine members for their products in return for a small fee. The program and fee guarantees reviews by requiring Vine members to review products.

The Amazon Vine analysis digs into a dataset containing reviews of pet supply products. PySpark is used to perform the ETL process by connecting to an AWS RDS instance and loading the data into pgAdmin. PySpark is also used to analyze the dataset and determine if there is bias toward favorable reviews from Vine members.

## Results: 

- How many Vine reviews and non-Vine reviews were there?
  - There were 170 Vine reviews and 37840 non-Vine reviews of the pet supply products.
      
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There were 65 Vine reviews and 20612 non-Vine review that were 5 stars.
      
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - The percentage of 5 star Vine reviews was 38.23% and 54.47% for non-Vine reviews.

## Summary: 

55% of reviews were from non-Vine members and 38% were from Vine members. This would suggest that there is not a bias toward favorable reviews from Vine members for pet products. Additionally, statistical analysis such as a two sample t-test could help quantify uncertainty caused by bias.
