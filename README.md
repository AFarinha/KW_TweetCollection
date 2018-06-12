# KW_TweetCollection
KW_TweetCollection consists of 25 twitter users (identified by the twitter user id), 8722 tweets (identified by the tweet id and collected on September 2017) and 39,967 corresponding relevant keywords (manually annotated by 15 volunteers). To guarantee its adaptability to different research purposes, we opt to provide two different accesses to KW_TweetCollection. 

	* Folder “all” gathers all the 8722 tweets and corresponding relevant keywords.
	* Folder “users” gathers the same number of tweets and corresponding relevant keywords but this time divided into 25 folders corresponding to each one of the 25 twitter users (identified by the user id).

The number of characters in the tweets was 140 characters even though the tweets could have a longer length. This problem should be to the twitter API that to get the full tweet it is necessary to activate a flag in the request.

```
Important:
The dataset is made up of "tweet id".key due to twitter's usage policies not allowing tweets to be shared. However, the content of the *.key file is made up of words considered as "keywords" by annotators who volunteered to perform this task.
```