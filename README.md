# Beer_Recommender
A beer recommendation system that will recommend new beer suggestions based on a users previous beer reviews.

# Project Goal and Business Case
* Provide beer recommendations for users of Beer Advocate’s beer review site. 
* Introduce users to new breweries and beer
* Develop brand and product awareness
* Increase user engagement in Beer Advocate’s website and with new breweries and beer

# Data
Data is from Beer Advocate's beer review website, sourced from https://www.kaggle.com/ehallmar/beers-breweries-and-beer-reviews?select=reviews.csv

# Recommendation Systems
* Content-Based 
  * Using natural language processing to find similarity in the user text reviews
* Item-Based Collaborative Filtering
  * Finding similarity between items calculated using user’s beer ratings and their cosine similarities
* User-Based Collaboratice Filtering
  * Finding similarity between users calculated using user’s beer ratings and the highest scoring SVD model

