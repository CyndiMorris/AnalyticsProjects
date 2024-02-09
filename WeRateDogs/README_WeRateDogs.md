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
[chicago.csv](https://video.udacity-data.com/topher/2019/February/5c747ce1_chicago/chicago.csv)  
[new_york_city.csv](https://video.udacity-data.com/topher/2019/February/5c747d01_new-york-city/new-york-city.csv)  
[washington.csv](https://video.udacity-data.com/topher/2019/February/5c747d10_washington/washington.csv)  
