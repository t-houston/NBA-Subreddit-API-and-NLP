# Reddit Pushift Web APIs & NLP

My client, the owners at Shwag Luxe Clothing (a high end clothing brand catered towards big and tall athletic menswear) wanted a better understanding of what and who American fans were frequently talking about so that they could figure out who to market to. My instructions were to surf through Reddit, the best social news site of our time, and find the best two SubReddit forums that will give the owners at Shwag,  Natural Language Processing models will allow us to accurately classify posts from each forum to identify who is hot, and who is not!

This project covers practicing and implementing three of the biggest concepts we learned in the immersive program and that are highly utilized in the data science industry: Classification Modeling, Natural Language Processing and Data Wrangling/Acquisition. 

For this project uses:
1\. Pushshift's API to collect posts from the NBA and NBA Discussion subreddits.
2\. NLP to train a classifier on this binary classification problem.

### Data Collection / Modeling

-   Gathered data using the `requests` library.
Using the NBA and NBA Discussion subreddits, I pulled the first 5000 posts using the Created UTC of the last post pulled. The shape of my data frame by the end of this was 10000 rows, and 90 columns. 
-   Created and compared Multinomial Naive Bayes, Logistic Regression with Count and TFIDF Vectorizers, and a Random Forest classifier models.


### Problem Statement

Determine which living nba player is most talked about (for better or for worse) in hopes of getting that player to be the face of your brand. Your owner knows nothing about basketball and is calling on the reddit community for help. I’m simply here to bridge the gap by evaluating subreddit forums and presenting my findings.
 
### Summary
Out of the top 15 most frequent words used in both subreddits, King (Lebron) James came 4th place overall, abut was the first most frequent player given the overall words. Michael Jordan was 10th place overall, making him 2nd for players mentioned in both subreddits.
