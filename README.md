# Amazon_Vine_Analysis
The Amazon Vine program allows manufacturers and publishers to use reviews for their products. We used the data from Amazon to determine the number of reviews in the video game category that they may see from this service and how valuable it might be against unpaid reviews. Using a mixture of AWS, Google Collab, and Postgres we were able to access the data from Amazon and transform, extract, and load the data into a clear manner.

## Results 

![](https://github.com/pbarana89/Amazon_Vine_Analysis/blob/main/Images/Total_Vine_Reviews.PNG)

![](https://github.com/pbarana89/Amazon_Vine_Analysis/blob/main/Images/Total_Non_Vine_Reviews.PNG)

![](https://github.com/pbarana89/Amazon_Vine_Analysis/blob/main/Images/Total_Helpful_Paid_Reviews.PNG)

![](https://github.com/pbarana89/Amazon_Vine_Analysis/blob/main/Images/Total_Helpful_Unpaid_Reviews.PNG)

- With no filtering there were 4,291 total vine reviews and 1,781,706 total non-vine reviews. If you were to include only reviews that received 20 or more helpful votes there were 94 paid reviews and 40,471 unpaid reviews.

![](https://github.com/pbarana89/Amazon_Vine_Analysis/blob/main/Images/Total_5_Vine_Reviews.PNG)

![](https://github.com/pbarana89/Amazon_Vine_Analysis/blob/main/Images/Total_5_No_Vine_Reviews.PNG)

![](https://github.com/pbarana89/Amazon_Vine_Analysis/blob/main/Images/Total_5_Vine_Helpful_Reviews.PNG)

![](https://github.com/pbarana89/Amazon_Vine_Analysis/blob/main/Images/Total_5_NoVine_Helpful_Reviews.PNG)

- With no filtering there were 1,607 total 5 star vine reviews and 1,025,317 total 5 star non-vine reviews. If you were to include only reviews that received 20 or more helpful votes there were 48 paid 5 star reviews and 15,663 unpaid 5 star reviews.

![](https://github.com/pbarana89/Amazon_Vine_Analysis/blob/main/Images/Total_Percentages.PNG)

- Either with filtering or a lack of filtering the amount of 5 star reviews that were vine reviews against the total amount of reviews is staggering. The paid 5 star vine reviews made up less than 1% of the reviews and unpaid 5 star reviews made up more than 99% of that number.

### Summary of the Vine Reviews
- There is no real positivity bias of the reviews in the Vine Program in the Video Game category. They make up such a small amount and their contribution is miniscule. We could look at another possible additional idea to see if any specific products received a large amount of vine reviews and perhaps if there was success for that product versus others.
