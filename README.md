# Twitter Keyword Tracker and Analysis

This Jupyter Notebook can be used to download tweets by a trending keyword filtering out retweets (you'll need your own Twitter API key) using Tweepy. The topic for this analysis was President Trump's impromptu visit to North Korea in June 2019.

The notebook ran a TextBlob sentiment analysis on the tweets, including a subjectivity and polarity analysis. Sentiment was plotted in histograms, pie charts, and WordClouds. Positive and negative tweets were returned. NLTK was used to run n-grams of the most common words found in the tweets, including unigrams, bigrams, and trigrams which were also plotted in barh charts using Matplolib. The timeframe that the tweets were created at were also plotted in a chart.
