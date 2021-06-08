# Udacity data analyst project3 - Wrangle and Analyze Data
## by Imesha Kuruppu

### Introduction
The main goal of this project is to perform data wrangling and store, analyze, visualize wrangled data. Finally, need to prepare a report on data wrangling effort(internal document) and another report on data analyses and visualizations(external document). During the data wrangling process, data need to be gather, assess and clean.

### What do I need to install?

* python
* pandas
* NumPy
* requests
* tweepy
* json

### Dataset
The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10.But, the numerator is always greater than 10. 11/10, 12/10, 13/10, etc. This rating system is unique to the 'WeRateDogs'. This unique rating system is a big part of the popularity of WeRateDogs.

### Project overview:
The goal of this project is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering,
then assessing and cleaning is required for better analyses and visualizations.

In this project, I have gathered, assessed, and cleaned data related to the 'WeRateDogs' Twitter account. Data have been gathered from three sources(CSV file, tsv file downloaded from a given URL, and Twitter API).
Then, assessed the data visually and programmatically to find quality and tidiness issues. Discovered issues were cleaned in the data cleaning step and finally, obtained a high quality and tidy master pandas DataFrame. This data frame was saved as the 'twitter_archive_master.csv' and used for analyzing, and visualizing data. Data wrangling effort was reported in the 'wrangle_report.pdf' report and analyzed data and visualizations were reported in 'act_report.pdf'.
