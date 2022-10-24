# Surfs_Up
## Purpose

The client, W. Avey is interested in opening his dream ice cream parlor and surf gear retail shop combo on the island of Oahu, Hawaii.  Given weather data from multiple weather stations on Oahu from 2010 to 2017, this project analyzes temperature data--specifically for the months of June and December-- to help W. Avey decide if his surf and ice cream shop business is sustainable year-round. 

The code in this project was develop so that it may also be utilized with similar weather data files and may be used to evaluate other potential sites for the shop as it is hoped that their success warrents expansion in the future. 

This project utilyzes Python, Pandas functions and methods, and SQLAlchemy to work with the weather data file provided in an sqlite database.
[hawaii.sqlite](https://github.com/ashleycvirga/Surfs_Up/blob/d76a18aa1bc49046673e33105ff676a6b6a19d2a/hawaii.sqlite)

Matplotlib was used to create additional visuals.

## Results

Below are the weather data summary statistics collected on Oahu, Hawaii for the months of June and December for the years 2010 through 2017:

![june_dec_stats.png](https://github.com/ashleycvirga/Surfs_Up/blob/d76a18aa1bc49046673e33105ff676a6b6a19d2a/Resources/june_dec_stats.png)

1. An initial glance at the data shows that there were approximatelt 200 less temperature observations gathered for the month of December.

2. The mean temperatures for both months only differ by about 4 degrees and are both in the low to mid 70's. Similary minor differences of less than 4 degrees can also be found between their temperatures in the 25%, 50%, 75% and max ranges.

3. The minimum or lowest temperature observation of 56 degrees farenheit for December is slightly more concerning than the 64 degrees farenheit observed for June.  However, the following histogram of December's observations explains that this low temp seems to be a rarer occurence for the month--with the majority of the observations in the 70-75 degrees range. 

![dec_hist.png](https://github.com/ashleycvirga/Surfs_Up/blob/d76a18aa1bc49046673e33105ff676a6b6a19d2a/Resources/dec_hist.png)

4. For comparison, the following histogram of June temperature observations shows a slightly smoother spread as expected from the standard deviations provided in our summary statistics.  The majority of temperature observations for the month of June consistenly fall within the 70 to 80 degrees farenheit range.

![june_hist.png](https://github.com/ashleycvirga/Surfs_Up/blob/d76a18aa1bc49046673e33105ff676a6b6a19d2a/Resources/june_hist.png)

## Summary
The results of this analysis show consistent temperatures in the 70 degree range and only minor differences of 4 degrees or less in temperatures for both the months of June and December on the island of Oahu. It seems to make it an excellent location for the client W. Avey to begin investing in his surf and ice cream shop business!  

Before making a final decision--or when analyzing future locations--I would recommend two additional queries to be performed.

  1. Gather and analyze rainfall and or humidity data as these can also play into perception of temperatures and potential surf activity. How many of our 70 - 80 
  degree days also experience rainfall? 
  
  2. While I went ahead and showed this in the histograms I created, additional queries to determine the exact instances of the minimum temperatures of 56 degrees and 64 degrees for the months of December and June(respectively) would also be beneficial. The histograms show that they are rare, but a query would show us for certain. 
  

## Software

Python v. 3.7.13

Jupyter Notebook v. 6.4.11

Numpy v. 1.21.5

Pandas v. 1.3.5

SQLAlchemy v. 1.4.39

Matplotlib v. 3.5.1

Flask v. 2.0.3
