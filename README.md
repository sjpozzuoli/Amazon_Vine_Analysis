# Amazon Vine Analysis

### The purpose of this is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We will use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we’ll use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results

![Amazon_Reviews_screenshot](https://user-images.githubusercontent.com/81929616/128653103-44136c38-3df0-4726-a029-5229cece9dde.png)

#### I chose to examine the category of "Sports" reviews on Amazon. There were three questions that needed to be answered for both Vine and Non-Vine reviews on certain products. Below are the findings.

1. There were a total of 334 reviews by Vine program members.
2. Of those 334 reviews, 139 of them were 5 star rated reviews.
3. The percentage of Vine 5 star rated reviews was 41.6%.
4. There were a total of 61,614 reviews by non-Vine program members.
5. Of those 61,614 reviews, 32,665 were 5 star rated reviews.
6. The percentage of non-Vine 5 star rated reviews was 53%.

## Summary

#### Overall, it seems as if members of the Vine program require higher standards to give out a 5 star review, as shown by the 41%, as opposed to the non-Vine members who give out 5 star ratings at a 53% clip. These results may be slightly skewed due to the fact that there are far more non-Vine program members than Vine program members. In order to verify these results, I think a good stufy would be to group a few different categories together and examine them to get a larger data set of Vine members into one analysis. This would provide a more accurate picture of whether or not there is a bias in ratings for Vine members.
