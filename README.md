# Data-Wrangling

## Introduction
The dataset I will be wrangling in this notebook is the is the tweet archive of WeRateDgs, account handle @dog_rates on twitter.

Data will be sourced from the files listed below, assessed, cleaned, and insights drawn from it.

- twitter-archive-enhanced.csv

- image-predictions.tsv

- tweet-json.txt


WeRateDogs is a Twitter account that posts and rates pictures of dogs. These ratings often are not serious and have numerators that are greater than the denominators. In this analysis, I mostly focus on wrangling WeRateDogs's Twitter archive through August 1, 2017. Most of the necessary Twitter data has been provided by Udacity and includes information on each post, as well as details on each dog such as the name, rating, and stage (whether the dog is a doggo, floofer, pupper, or puppo). See below for definitions on the dog stages. However, not all of the desired data is present in Udacity's dataset, so I also use the Twitter API to gather additional data.

The approach taken analyzing this data is 
          - Data Gathering - collecting data from different sources(alternative code to fetch data from Twitter using Tweepy API is included)
          -  Data Assessing - Identifying tidiness and cleanliness issues in teh data
          - Data Cleaning - Sorting out the issues identified in the assessing stage and testing efficacy of actions taken
          - Storing Data - Downloading the clean merged dataset
          - Data Analysis and Visualization - Using the cleaned dataset to visualize findings
