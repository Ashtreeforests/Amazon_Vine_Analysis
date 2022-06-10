# Amazon_Vine_Analysis

## Objective
Analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Typically, companies pay a small fee to Amazon and provide products to Amazon Vine members. These members who receive these products are then required to publish a review. The majority of Amazon shoppers factor product reviews in their online purchase decisions. Vine reviews are usually large so this will likely exceed the capacity of local machines to handle. For this reason, Spark and AWS are tools used to perform the ETAL process completely in the cloud and upload a Dataframe to an RDS instance. PySpark is used to perform the statistical analysis of the selected data. 

## Results
### Total number of reviews

* Vine reviews

![image](https://user-images.githubusercontent.com/96931376/172972320-fe4284de-166d-4d6a-ba12-18b7f4ab8c0c.png)

* non-Vine reviews

![image](https://user-images.githubusercontent.com/96931376/172972383-fa800f87-4cd2-4537-941a-d62e12cbc249.png)

### Total number of 5-star reviews

* Vine reviews

![image](https://user-images.githubusercontent.com/96931376/172972432-6af3d3a2-ffa9-4361-9b8b-157b57509452.png)

* non-Vine reviews

![image](https://user-images.githubusercontent.com/96931376/172972477-051091e5-a3f4-40dd-b954-3f53e11fbe7e.png)

### Percentage of 5-star reviews

* Vine reviews

![image](https://user-images.githubusercontent.com/96931376/172972529-9470b21a-9ce9-4986-a9eb-842b83300f58.png)

* non-Vine reviews

![image](https://user-images.githubusercontent.com/96931376/172972539-9f47f01f-8fe6-4a3d-83b2-18e670c3a2fc.png)

## Summary and Bias of Vine Reviews
Bias can be presumed in this Amazon Vine program as members are essentially being paid for their opinion with the intent to share to a wide audience. This is evident when we compare the star ratings of a product between vine reviews and non-vine reviews. A positivity bias for reviews was statistically demonstrated in the Vine program. 

* 51% of the Vine reviews were 5 stars
* 39% of the non-Vine reviews were 5 stars
