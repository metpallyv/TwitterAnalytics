# TwitterAnalytics using Twitter RestApis
The goal of this project is to be able to perform Twitter Analytics using the Twitter Rest APIs

The reason for this project is that I want to perform two things using Twitter tweets:

1. Sentiment Analysis of Tweets.

2. I wanted to estimate US Congressmen's stance on a particular political issue/bill. For example, 
   I want to capture Donald Trump's political ideology using his tweets and friends information on Twitter. 
   Furthermore, if we make use of the text information of users’ tweets, especially retweets, to better understand political       figure’s emphasis on different topics. If Donald Trump follows Hillary CLinton on Twitter and if he retweets lots of
   postive tweets of Hillary clinton related to Iran Nuke bill, we can predict that Donald Trump would vote postively for 
   that Iran Nuke bill.

#Twitter Crawler 
This application does the following using Twitter REST APIs:

1. Authenticates my twitter application(MiningInfo) for Analytics on Twitter using OAuth
2. Returns entire Twitter profile information based on the username/twitter-id provided
3. Returns Twitter followers info (names,twitter ids, etc) for each twitter user/twitter-id provided.
4. Returns Twitter Statuses for each twitter user provided
5. Returns Twitter friend's ids for each twitter user provided
6. Returns Tweets based on the keyword search on Twitter.
7. Returns retweets by a user

crawls through each and every US congressmen's Twitter account and
    1. Returns the US congressmen followers for each US congressmen
    2. Tweets for each US congressmen
    3. Retweets for each US congressmen.


