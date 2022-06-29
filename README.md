# Amazon_Vine_Analysis


## Analysis Overview

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.


## Resources

Data Source: Amazon Review datasets, Video Games Review dataset
Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

 
## Results

## Total number of reviews


![Screen Shot 2022-06-29 at 2 03 34 AM](https://user-images.githubusercontent.com/100106554/176363747-36d0a47b-53c5-4707-bb64-2fbd109cb4b4.png)



## Total number of 5-Star reviews

![Screen Shot 2022-06-29 at 2 03 55 AM](https://user-images.githubusercontent.com/100106554/176363203-e03f6b20-d3d6-47a6-b349-71b1c0bbda19.png)



![Screen Shot 2022-06-29 at 2 04 01 AM](https://user-images.githubusercontent.com/100106554/176363222-ae0b0963-3df2-416a-9b18-6e0325340724.png)

## Percentage of 5-star reviews


![Screen Shot 2022-06-29 at 2 03 48 AM](https://user-images.githubusercontent.com/100106554/176363177-5c9c34c8-8116-41fc-bd90-a7a93643b1e2.png)



![Screen Shot 2022-06-29 at 2 04 06 AM](https://user-images.githubusercontent.com/100106554/176363238-a452fb0a-4c36-4f9f-b8b2-c752e5814d4e.png)



## Summary

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
