# NetflixOC
Analysis of Netflix's Original content with data from February 2013 to May 2017 

Author: Hunter Kempf

## Installations
This project requires installation of the following python packages: 
1. Pandas
1. Numpy
1. Sklearn
1. Matplotlib

## Project Motivation
Netflix is a company that I am interested in especially because they are a leader in the streaming media business that many large content companies are trying to emulate. Despite this they have a bit of a reputation for producing almost anything they can get and seem to at least in the eyes of the public take a Quantity over Quality approach. I am interested in diving into data about the shows they fund to get more insights into their approach to content creation.

## Executive Summary

### Monthly Analysis

Netflix is stepping up their original content production and from 2013 to mid 2017 has gone from one show premier every other month

### Yearly Analysis

The average show rating per year premiered is declining as netflix is making more shows. 

### High Rating Analysis

There aren't any clear trends in show length or number of episodes for highly ranked shows.

### Genre Analysis

There are clear associations of genre's with IMDB ratings. This shows the areas that netflix is succeeding in with their original content. this seems to mostly be around Drama's, Marvel shows and Docu-Series. It would be interesting to see how this compares with other major content producers (Disney, Warner Media etc)

### Status Analysis

IMDB rating seems to have a correlation with the Status of the show and at a high level aligns with the various levels of Status from Ongoing to Ended. 

### Status Predictions

Despite not having much data to work with and using a simple model the accuracy in predicting the Status of a show is pretty decent. It would be interesting to get more general data on other companies and content to see how it can compare.

## Next Steps / Areas for Improvement

### Next Steps

1. I would like to extend analysis like this to other content creation companies like Disney or Warner Media
    - This would likely require building my own dataset through webscraping
    - This could allow me to pull ratings from other sources than IMDB as well as bring in new features like cost of production or Director/Cast information
1. I would like to see how my simple model performs on more recent data 
    - This would require me to extend the dataset through to 2019 which would probably have to be done through webscraping 
1. Since this analysis only covers series I would like to extend it to Movies as well since Netflix especially recently has been making more of those

### Areas for Improvement

1. This Analysis really lacks the ammount of Data that I would like to have (only 109 observations)
1. This Data has pretty limited feature information about a show

## File Descriptions
The file structure in this project is very simple:
1. Netflix_Originals_EDA.ipynb 
    - This is the jupyter notebook that I wrote my python code in for my analysis of the Netflix Dataset
1. Netflix_Originals_EDA.html 
    - This is an html file that was compiled from the jupyter notebook
 
