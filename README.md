# Amazon Vine Analysis

### The purpose of this is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We will use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we’ll use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

![Amazon_Reviews_screenshot](https://user-images.githubusercontent.com/81929616/128653103-44136c38-3df0-4726-a029-5229cece9dde.png)

#### I chose to examine the category of "Sports" reviews on Amazon. There were three questions that needed to be answered for both Vine and Non-Vine reviews on certain products. Below are the findings.

1. There were a total of 334 reviews by Vine program members.
2. Of those 334 reviews, 139 of them were 5 star rated reviews.
3. The percentage of Vine 5 star rated reviews was 41.6%.
4. There were a total of 61,614 reviews by non-Vine program members.
5. Of those 61,614 reviews, 32,665 were 5 star rated reviews.
6. The percentage of non-Vine 5 star rated reviews was 53%.

