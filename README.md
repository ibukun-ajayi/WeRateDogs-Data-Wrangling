# WeRateDogs-Data-Wrangling
The archived tweets of Twitter user @dog rates, better known as WeRateDogs, were wrangled, analyzed, and displayed as part of the requirenment towards the completion of the Udacity Nanodegree program. 
WeRateDogs assigns ratings to people's dogs along with a witty commentabout the dog. 
This report describes the wrangling effort applied for the completion of the project. The wrangling process followed for the project are; 
Data Gathering 
Data Assessment
Data Cleaning 
Providing insights based on the clean data Data wrangling efforts
The data required for the project consist of three datasets obtained as follows;
WeRateDogs Twitter archive data (twitter_archive_enhanced.csv) provided by Udacity andread manually into a dataframe "arch"
Tweet Image Prediction(image_prediction.tsv) hosted on Udacity server and was retrieved progarammatically using the requests library and the provided url. 
Then the tsv file was readinto a dataframe "predict"
Twitter API & JSON: Used the tweet IDs in the WeRateDogs Twitter archive to query theTwitter API for each tweet's JSON data using Python's Tweepy library and stored eachtweet's entire set of JSON data in a file called tweet_json.txt file. 
Then read line by line into apandas DataFrame "json_tweet". For the twitter API to be queried, i applied for accessthrough the twitter developer portal.
