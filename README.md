# Overview
In this project we pull our data from Reddit to use NLP/Sentiment analysis and Classification models on two separate subreddit columns.

# Problem Statement
A software company would like to develop a photo and video editing software for mobile phones, but can only produce it for one mobile phone operating system due to financial constraints.
Determine which mobile phone OS (iPhone or Android) this company should develop their app for purely based on Reddit posts under each platform’s subreddit category.


# Data Dictionary 

## Dataframes
|df_name|file_name|Description|
|---|---|---|
|iphone|iphone.csv|iphone subreddit data|
|android|android.csv|android subreddit data|
|android_top_words|android_top_words.csv|android top 25 words|
|iphone_top_words|iphone_top_words.csv|iphone top 25 words|
|cleaned_df|cleaned_df.csv|cleaned up concatenated version of iphone and android datasets|

## Dataset column types

|column|type|
|---|---|
|subreddit|Object|
|selftext|Object|
|title|Object|

# Conclusion
Based on the sentiment scores for the most popular and relevant words found in each subreddit column, Android seems to be the higher favored operating system for photo and video. This would be the ideal operating system to produce a photo and video editing application. 
