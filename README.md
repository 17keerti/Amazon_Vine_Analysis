# Amazon_Vine_Analysis

## Overview of the analysis

In this analysis i have analyzed Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. I have reviewed dataset of shoes and used PySpark tp perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, i have used PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results

### Totral reviews

- There were total 22 Vine(paid) reviews and 26987 non-Vine(unpiad) reviews.

### 5-star reviews

- 13 paid reviews were 5 stars and 14475 unpiad reviews were 5 stars.

### Percentage of 5-star reviews

- 59.09 % of the paid reviews were 5 stars and 53.63% of the unpaid reviews were 5 star.

  ![Paid reviews](./Images/paid.png)
  ![Unpaid reviews](./Images/unpaid.png)

## Summary

As can be seen from the result above, there is no positivity bias for reviews in the Vine program, considering 59 % of paid reviews were 5 stars and 53% of unpaid reviews were 5 stars. Hence, Vine members didn't show any bias when rating their products. We can further examine by calculating statistical distribution(mean, median, mode) of the reviews.
