# twitter_live_data
Live Tweets extraction from twitter using tweepy package in Python
- In this project we extracted live data from twitter using the tweepy package.
- In tweepy package we are concerned with the StreamClient which gets live data from twitter.
- To extract live data from twitter we need to get API key, API secret key, Acess token and Acess secret token from Twitter.
- Try to get elevated API key as it gives you access to 2M tweets per month.
- The code uses rules to get data restricted to certain keywords. These rules can be changed.
- However, when you change rules, the previous rules are still in the database of rules. So make sure to delete those before changing rules.
- A limit can be set as to how many tweets are required to be extracted. I have set the limit to 25000.
- This data can be put into a DataFrame and used for NLP project such as Sentiment Analysis.
