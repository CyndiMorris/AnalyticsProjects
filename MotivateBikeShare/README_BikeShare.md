# Project: Motivate Bike Share Data - R Programming
* **Note:** Please click on File: Motivate_Bike_Share R >>> MotivateBikeShareR.md to see project.

## Project Details  

Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.

Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

This project will compare the system usage between three large cities: Chicago, New York City, and Washington, DC. Three questions will be asked and answered via exploration and visualizations.

## Analysis and Statistics

Question 1:
Which rental days are the most popular in each city?

Question 2:
What are the top 5 Start Stations for each city?

Question 3:
What are the user percentages for Customers and Subscirbers in each city?  
* **Note**: 'Customers' are users who pay as they go/need. 'Subscribers' use pre-paid usage plans.

## Datasets

The datasets for this project were provided by [Motivate](https://motivateco.com/), a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. 

Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:  

Start Time (e.g., 2017-01-01 00:07:57)  
End Time (e.g., 2017-01-01 00:20:53)  
Trip Duration (in seconds - e.g., 776)  
Start Station (e.g., Broadway & Barry Ave)  
End Station (e.g., Sedgwick St & North Ave)  
User Type (Subscriber or Customer) 

The Chicago and New York City files also have the following two columns:  

Gender  
Birth Year  

<img src="https://github.com/CyndiMorris/assets/blob/main/3CityData.jpg" width="1200"/>


The original files are much larger and messier, containing more columns and differed in format in many cases. Some data wrangling has been performed to condense the files to the above core six columns to make analysis and the evaluation of R skills more straightforward.  

Note: I did some additional manipulations in Excel before readnig into Jupyter.  
* Concatenated files for Chicago, New York City and Washington DC
* Changed and unified column naming conventions 
* Split Start Time and End Time into separate date and time columns
* Added Columns to df: City, Start.Date, Start.Time (hhmm), Weekday, End.Date, End.Time (hhmm), Trip.Duration (h:mm:ss), Trip.In.Sec, Age

## Software and Packages
R  
repr  
scales  
ggplot2  
Jupyter Notebook  
Excel  

## Files
[chicago.csv](https://video.udacity-data.com/topher/2019/February/5c747ce1_chicago/chicago.csv)  
[new_york_city.csv](https://video.udacity-data.com/topher/2019/February/5c747d01_new-york-city/new-york-city.csv)  
[washington.csv](https://video.udacity-data.com/topher/2019/February/5c747d10_washington/washington.csv)  

