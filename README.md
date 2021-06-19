# Amazon_Vine_Analysis
Performing ETL on a database from Amazon.

## Overview 
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Various Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Out task was to use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We used PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.


## Results

#### There were total 47 Vine Reviews.

![image](https://user-images.githubusercontent.com/78935551/122655787-3cdb5600-d123-11eb-9cf9-a2065ff9b1d8.png)


#### There were total 8362 non-Vine Reviews.

![image](https://user-images.githubusercontent.com/78935551/122655799-5da3ab80-d123-11eb-9c3b-43594869f46c.png)

#### 15 Vine reviews were 5 Stars.

![image](https://user-images.githubusercontent.com/78935551/122655838-ac514580-d123-11eb-97f8-cdd404339fa2.png)


#### 4332 non-Vine reviews were 5 Stars.

![image](https://user-images.githubusercontent.com/78935551/122655864-ed495a00-d123-11eb-9fc8-943544cc3430.png)


#### Approx 32% of Vine reviews were 5 Stars.

![image](https://user-images.githubusercontent.com/78935551/122655876-0d791900-d124-11eb-873c-4648c4d9c9af.png)


#### Approx 51.8% of non-Vine reviews were 5 Stars.

![image](https://user-images.githubusercontent.com/78935551/122655906-3d282100-d124-11eb-849d-924b6113f416.png)





