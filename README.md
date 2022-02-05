# Amazon_Vine_Analysis
## Overview
####
The company, SellBy, participates in a program with Amazon and consumers called the Amazon Vine program. This particular program lets SellBy provide items to a consumer and then is guaranteed a product review. Amazon has several sets of data to peruse, however, SellBy is simply interested in what a data set looks like when statistically comparing paid and unpaid (or Vine versus non-Vine consumers) reviews. In this particular analysis, a dataset containing reviews for books sold through Amazon was analyzed to understand the trends of non-paid and paid for reviews. This analysis will help stakeholders at SellBy understand if their is a bias with paid reviews through the Vine program. 

## Results
####
Below are the results of the statistical analysis of Vine and non-Vine reviews. 

- When comparing Vine reviews and non-Vine reviews, it was clear that the non-Vine reviews greatly outnumbered Vine customers' review count. In total, there were 4,781 Vine reviews and 332,395 non-Vine reviews. 
####
![vineReviewCount](https://github.com/victoriaguille/Amazon_Vine_Analysis/blob/main/resources/vineReviewCount.PNG) ![nonVineReviewCount](https://github.com/victoriaguille/Amazon_Vine_Analysis/blob/main/resources/nonVineReviewCount.PNG)
####
- If one were to look at only 5 star reviews, Vine reviews had 1,604 5-star reviews and non-Vine users gave 168,800 5-star reviews. 
####
![vineFiveStars](https://github.com/victoriaguille/Amazon_Vine_Analysis/blob/main/resources/vineFiveStars.PNG) ![nonVineFiveStars](https://github.com/victoriaguille/Amazon_Vine_Analysis/blob/main/resources/nonVineFiveStars.PNG)
####
- The final statistical comparison showed that both non-Vine and Vine consumers leaned towards leaving 5-star reviews over other star ratings. Of the Vine reviews, there were 33.55% votes that were 5-stars. Of the non-Vine reviews, 5-star reviews made up 50.78% of the total. 
####
![vinePercentage](https://github.com/victoriaguille/Amazon_Vine_Analysis/blob/main/resources/vinePercentage.PNG) ![nonVinePercentage](https://github.com/victoriaguille/Amazon_Vine_Analysis/blob/main/resources/nonVinePercentage.PNG)

## Summary
####
After performing the statistical analysis of both the Vine and non-Vine reviews, it is clear that both types of users are more inclined to provide five star reviews as seen in the different break downs above. However, it appeared that those who were not paid to review a product were more likely to give a five star review overall, with the data showing that over half of the reviews analyzed were five star reviews. In comparison, Vine users also had the five star rating as the most frequent choice, but only a third of the time. The data between non-Vine and Vine reviews varied greatly in size. Non-Vine reviews dominated in numbers and still maintained an extremely high five star rating percentage out of roughly 332,000 reviews. From the statistical analysis, it isn't overly obvious that there is a bias towards inflating Vine reviews purely because the consumer is being paid to review the book. If SellBy stakeholders did not find this data set sufficient due to subject matter (books), another analysis ran the exact same way could be performed on a more popular product type to test this hypothesis. However, if the SellBy stakeholders are wanting to look further into this specific data set from Amazon, comparing the count of helpful votes could prove even further that consumers as a whole would not be biased toward Vine reviewers.
