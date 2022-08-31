# Project: WeRateDogs Twitter Archive 

## Introduction
WeRateDogs is a Twitter account that rates people's dogs. 
In this project, I created analyses and visualisations based on these dog ratings, their breeds as classified using an image prediction file and then retweet and favoutite counts on Twitter

## Data Gathering
For this project, the data I used which was gathered from 3 different sources are:
- twitter_enhanced_archive.csv which was manually downloaded from Udacity’s 
server.
- image_predictions.tsv which was downloaded programmatically from Udacity’s 
server using the Requests library. 
- tweet_json.txt which was obtained by querying the Twitter API for each tweet’s 
JSON data (tweet id, favourite count and retweet count) using python’s tweepy 
library and storing it.


## Insights from the Wrangled Data
After assessing, cleaning and joining the 3 data sources, these are the insights I got.

- 12/10 is the most common dog rating.
- There is a strong positive relationship between retweet count and favourite count.
- The most popular breeds of dogs are Golden Retriever, Labrador Retriever, Chihuahua, 
Pembroke, Pug, Poodle, Chow, Pomeranian, Samoyed and Malamute. 
- The most liked breeds (i.e breeds with the highest favourite counts) are the Golden Retriever, 
Labrador Retriever, Pembroke, Chihuahua, French Bulldog, Samoyed, Chow, Cocker Spaniel, 
Pug and Malamute.
- The breeds with the highest retweets are Golden Retriever, Labrador Retriever, Pembroke, 
Chihuahua, Samoyed, Cocker Spaniel, French Bulldog, Chow, Pug and Malamute. 
- Samoyed has the highest average rating which is 11.75/10.