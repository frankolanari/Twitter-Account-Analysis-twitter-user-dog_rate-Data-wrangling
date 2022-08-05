# Wrangle-And-Analyze-Data
_Data Wrangling, Data mining, API, Data Exploration (EDA)_

## Introduction
This project demonstrates the data wrangling process for analyses of the twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. In this report I will provide a brief description of the data wrangling techniques that were used to gather, assess and clean the data to be used for analyses.

### Gathering the Data
I gathered the data from three sources, of which I have listed below;

- **The WeRateDogs Twitter archive** - This file (archive.csv) was downloaded manually and consists of basic tweet data for 2300+ tweets from WeRateDogs. This was download manually from Udacity.

- **The tweet image predictions** - This hold contain data about the breed of dog based on the image of the tweet, however it's a prediction and not 100% accurate, the prediction is made a neural network. This file (image_predictions.tsv) was downloaded programmatically from the link provided on the Udacity platform.

- **Additional data from the Twitter API** -This file (tweet_json) contains JSON data for each tweet indicating the retweet and like counts. This data was programatically extracted from twitters api. I stored the data extracted into a csv file for convience.


The data gathered were loaded in seperate dataframes and assessed visually and programatically for quality and tidyness issues.

_**You Can find more detailed information regarding this project in the 'project report' I attached in this repository.
