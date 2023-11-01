
# Sentiment_Analysis_on_Amazon_food_reviews

## Project Summary:
- Using the Amazon product reviews dataset, I have created a model that predicts whether a given review is positive or negative.
- This is to help firms to improve the quality of products and services based on users reviews. 
- Many businesses out there look at the reviews and make the required changes. 
- SO, this is the project that helps firms to easily predict the sentiment of user reviews. 
- I have performed Data preprocessing, Data Visualization, Converting the Text into Vector using Natural Language Processing, Random Over Sampling to resample the data i.e to convert the data into balanced data, thereby predicting the accuracy using multiple NLP techniques and machine learning algorithms. 
- Finally, I got the accuracy of 0.987 by using the GridSearchCV().

## Dataset information:
- This dataset consists of reviews of fine foods from amazon.
- The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. 
- Reviews include product and user information, ratings, and a plaintext review. We also have reviews from all other Amazon categories.

## Dataset statistics:
1. Number of reviews- 568,454
2. Number of users- 256,059
3. Number of products-	74,258
4. Users with > 50 reviews-	260
5. Median no. of words per review-	56
6. Timespan-	Oct 1999 - Oct 2012

## Data format:
1. product/productId: asin, e.g. amazon.com/dp/B001E4KFG0
2. review/userId: id of the user, e.g. A3SGXH7AUHU8GW
3. review/profileName: name of the user
4. review/helpfulness: fraction of users who found the review helpful
5. review/score: rating of the product
6. review/time: time of the review (unix time)
7. review/summary: review summary
8. review/text: text of the review

## Data Source:
[snap.stanford.edu](https://snap.stanford.edu/data/web-FineFoods.html)
