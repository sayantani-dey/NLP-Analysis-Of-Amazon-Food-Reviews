# NLP-Analysis-Of-Amazon-Food-Reviews
In this NLP analysis we check whether the sentiment scores of the reviews match the star ratings given by customers.

This analysis can provide valuable insights for business and researchers as following: 
  1.  In cases where sentiment scores do not match star ratings, it may indicate anomalies or inconsistencies in the data. For example, if a review contains negative sentiment words but is accompanied by a high star rating, it could suggest fraudulent or biased reviews.
  2.  Understanding the relationship between sentiment scores and star ratings can help businesses gain deeper insights into customer feedback. For instance, if most positive reviews (high star ratings) also have high sentiment scores, it suggests that customers are generally satisfied. Conversely, if there are low sentiment scores for positive star ratings, it may indicate that customers have high expectations and are harder to please.
  3.  Analyzing the discrepancies between sentiment scores and star ratings can help businesses identify areas for improvement. For example, if negative sentiment is prevalent in reviews with high star ratings, it may highlight aspects of the product or service that customers find lacking.

This repository for a natural language processing (NLP) analysis of Amazon fine food reviews was conducted using the following steps:
  1. Exploratory data analysis (EDA) was performed on the dataset to identify any patterns or trends.
  2. The NLTK library was used to check the polarity of the sentences in the reviews.
  3. The results of the polarity check were merged with the dataset using VADER's approach.
  4. An assumption was tested, which was that the highest star rating (5) would receive the most positive scores and the lowest star rating (1) would receive the most negative scores.
The results of the analysis showed that the assumption was correct. The highest star rating (5) received the most positive scores, while the lowest star rating (1) received the most negative scores. This suggests that the polarity of the reviews is correlated with the star rating.
  5. Textblob method was also used to check for the same and a comparison between the results of VADER's and TextBlob was plotted.
