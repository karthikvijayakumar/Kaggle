# Motivation

The Seattle AirBnB dataset is a popular dataset for analysis. My objective was to go through it, analyze it and ask questions that have likely not been asked before. My [blog post on medium](https://medium.com/@karthikvijayakumar/airbnb-listings-in-seattle-a-deeper-look-4fc4dad3e34e) summarizes the analysis for a non-technical audience. 

This analysis was part of the Udacity Data Scientist nanodegree program. 

# Files

1. Seattle_AirBnB_exploration.ipynb

This is the jupyter notebook that contains the code written for the analysis. It starts with understanding the various attributes in the data and then moves into asking and answering various questions on the same.

# Libraries used

pandas, numpy, matplotlib, seaborn, calendar

# Setup required to reproduce results

In whichever folder the jupyter notebook is, you would need to create a subfolder called seattle_data_airbnb which would host the data files from [Kaggle](https://www.kaggle.com/airbnb/seattle). Say the jupyter notebook is in folder X, the following folder structure should exist:

X
<br>|-Seattle_AirBnB_exploration.ipynb
<br>|-seattle_data_airnbnb
<br>|--|-calendar.csv
<br>|--|-reviews.csv
<br>|--|-listings.csv

# Summary of results

I looked at 3 broad areas - availability, long term renting and neighbourhood variations. The high level takeaways were as follows:

1. Listings in Seattle peak in availability towards the end of the year and hit their lows in January, July, and August. They are equally available on weekdays and weekends.
2. There is some discount that one could get for renting a listing for a week or a month, but it has a wide variance and can even be negative.
3. Most listings are concentrated in Central Seattle. Prices are the highest there and the availability is the lowest there as well.

# Acknowledgements

I must ofcourse thank Udacity. This work was done as part of the Data Scientist Nanodegree, I am pursuing from Udacity.

Some other resources that helped me with the analysis or provided me with inspiration were:

1. [Josh Bernhard's blog on comparing AirBnB homes in Seattle and Boston](https://medium.com/@josh_2774/a-comparison-of-airbnb-homes-seattle-vs-boston-cdc0df2cfcd7)
2. [Inside AirBnB](http://insideairbnb.com/seattle/#)
	Inside AirBnB helped me visualise the dataset and understand some of the attributes given in the dataset


# Future work

Some explorations which could be done in the future.

1. Understand key factors that drive the pricing of a house
	One could guess location is a key predictor given there significant variation in prices across neighborhoods. A couple of questions just on that are:
	1. How much variance exists in prices within a neighborhood?
	2. Do reviews affect the pricing of a house?
2. Visualising the neighbourhood variations by generating a heatmap on the map of Seattle
3. Sentiment analysis of the reviews
4. Extend the analysis to the [Boston dataset from AirBnB](https://www.kaggle.com/airbnb/boston)
5. Compare and contrast, Boston and Seattle.
