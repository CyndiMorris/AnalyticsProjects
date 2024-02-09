# Project: WeRateDogs - Python, Data Wrangling & Analysis

## Project Details  


## The Datasets

In this project, you will work on the following three datasets.

Enhanced Twitter Archive

The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356).
 
Extracted data from tweet text
The extracted data from each tweet's text

pic goes here  

I extracted this data programmatically, but I didn't do a very good job. The ratings probably aren't all correct. Same goes for the dog names and probably dog stages (see below for more information on these) too. You'll need to assess and clean these columns if you want to use them for analysis and visualization.

 pic goes here 
Dogtionary from WeRateDogs book

The Dogtionary explains the various stages of dog: doggo, pupper, puppo, and floof(er) (via the #WeRateDogs book(opens in a new tab) on Amazon)

Additional Data via the Twitter API

Back to the basic-ness of Twitter archives: retweet count and favorite count are two of the notable column omissions. Fortunately, this additional data can be gathered by anyone from Twitter's API. Well, "anyone" who has access to data for the 3000 most recent tweets, at least. But you, because you have the WeRateDogs Twitter archive and specifically the tweet IDs within it, can gather this data for all 5000+. And guess what? You're going to query Twitter's API to gather this valuable data.

Image Predictions File

One more cool thing: I ran every image in the WeRateDogs Twitter archive through a neural network(opens in a new tab) that can classify breeds of dogs*. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).
 pic goes here  

  
## The Statistics Computed

Question 1:


Question 2:


Question 3:

## Project Steps Overview
The tasks in this project are as follows:  
* Step 1: Gathering data  
* Step 2: Assessing data  
* Step 3: Cleaning data  
* Step 4: Storing data  
* Step 5: Analyzing & visualizing data    
* Step 6: Reporting    
•	your data wrangling efforts   
•	your data analyses and visualizations


## Built With
Pandas
Numpy
Requests
json
Matplotlib
Jupyter Notebook

## Files Used
•	[twitter_api.py](https://video.udacity-data.com/topher/2018/November/5be5fb4c_twitter-api/twitter-api.py)  
•	[tweet_json.txt](https://video.udacity-data.com/topher/2018/November/5be5fb7d_tweet-json/tweet-json.txt)


Overview
The goal of this project was to Wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations, and specifically to:

Perform data wrangling (gathering, assessing and cleaning) on provided thee sources of data.
Store, analyze, and visualize the wrangled data.
Report on 1) data wrangling efforts and 2) data analyses and visualizations.
In addition, as per project specificacion, only original tweets/ratings that have images should be used in the analysis (no retweets nor replies).

This project was completed as part of Udacity's Data Analyst Nanodegree certification.

Data Origin
We Rate Dogs is a Twitter account with funny or interesting facts and pictures about dogs (mainly)...

Results
The data wrangling process (data collection from different sources, data assessing and cleaning) resulted in two analytics-ready datasets used for a simplified analysis (full analysis is out of scope of this exercise).

Details
Data wrangling on Twitter datasets (Jupyter notebook online HTML version)
Data wrangling on Twitter datasets (Jupyter notebook online version, 11MB)
Data wrangling report (PDF)
Data analysis insights (PDF)
Statistical Analysis Scope
Basic descriptive statistics
Timeseries visualization using moving (rolling) averages
Tools
Python
Jupyter Lab
Libraries: pandas, numpy, requests, tweepy, datetime, os, json, matplotlib
