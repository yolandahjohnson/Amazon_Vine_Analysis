# Amazon_Vine_Analysis

## Overview
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Utilizing an Amazon Review dataset, I first used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. I then used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

I chose to analyze the Shoe review dataset. 
 
## Results
There are a total of 27,009 reviews.

![total number of reviews](https://user-images.githubusercontent.com/100816778/177208509-e06205d5-a3c1-4b7d-ad5b-cdeecc60523b.png)

- How many Vine reviews were there?

There are a total of 22 paid Vine reviews.

![total number of paid reviews](https://user-images.githubusercontent.com/100816778/177209246-e09f9262-6953-4ef0-bd95-a18047863f92.png)

- How many non-Vine reviews were there?

There are a total of 26,987 non-Vine reviews.

![total number of unpaid reviews](https://user-images.githubusercontent.com/100816778/177209434-baddced8-c6da-446d-9076-529870c4aa8f.png)

- How many Vine reviews were 5 stars?

There are a total of 13 five-star Vine reviews.

![total paid 5-star reviews](https://user-images.githubusercontent.com/100816778/177209601-7b5ee0b2-417a-4a0a-8c57-4b547d7381f2.png)

- How many non-Vine reviews were 5 stars?

There are a total of 12,512 five-star non-Vine reviews.

![total 5-star unpaid reviews](https://user-images.githubusercontent.com/100816778/177209739-4f5e9747-3952-4e54-9e31-6828c7d9c688.png)

- What percentage of Vine reviews were 5 stars? 

The percentage of total 5-star Vine reviews of total Vine reviews was 59%

![% of total 5 star reviews of total Vine reviews](https://user-images.githubusercontent.com/100816778/177210540-4edfd4e7-9728-4a8c-8255-f0180576bac1.png)

- What percentage of non-Vine reveiws were 5 stars?

The percentage of total 5-star non-Vine reviews of total non-Vine reviews was 46%

![% of total 5 star reveiws of total nonVine reviews](https://user-images.githubusercontent.com/100816778/177210744-4b515ba9-9ffb-4c50-b0a7-bfc6b0ab4326.png)


## Summary
The results from the analysis indicate a positivity bias towards the Vine program. Looking at the percentages, 59% of total Vine reviews were 5-star reviews, compared to 46% of 5-star reviews of total non-Vine reviews.

