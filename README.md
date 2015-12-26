# How Twitter reacts to Emmy Awards 2015

A classifier for emotion analysis (positive and negative) of tweets related to each nominees and winners at Emmy Awards 2015

Plot generated -> https://plot.ly/~chitesh/31/how-twitter-reacts-to-emmys/

Dataset- Tweets crawled from Twitter using Tweepy's REST/cursor and Streaming API

./Data/pos.txt -> list of positive words showing positive emotions

./Data/neg.txt -> list of negative words showing negative emotions

./Data/EmmyN.txt -> list of original name, screen name, alias names and Twitter handle  of the Nominees

./Data/tweet_output_clean.txt -> Tweets crawled, parsed and cleaned for mining

./Output -> shows different categorize of output data

emmys-emotion.py -> Crawls Twitter for tweets, parses and cleans the tweets, mines the results and generates the visualization 
