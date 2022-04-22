# Covid Twitter Analysis

This repository covers a big data project which aims to anticipate rise in covid related cases and covid related deaths through analysis of pertinent tweets. 

### School: 
    University of Chicago
### Program: 
    Master of Science in Analytics (MScA) 
### Class: 
    Big Data Platforms MSCA 31013 2
### Professor: 
    Nikolay Kadochnikov

### Structure of the repository: 
1. Notebook: 
  The final jupyter notebook which contains all data cleaning and data analysis carried out in PySpark. 
2. Slides: 
  A powerpoint summarizing key findings, exploratory data analysis, future recommendations and the business value of this project. 

#### Detailed Project Description: 

I filtered through and ran pertinent analyses on a raw dataset of ~100M covid related tweets (roughly 600 GB worth of data). The project utilized clusters spun up on Google Cloud Project (GCP) and was primarily implemented through PySpark. The key steps which were taken to anticipate surge in Covid cases and covid deaths in relation to Tweets were the following: 

1. Discarding irrelevant tweets 
2. Complete thorough EDA to identify which variables to use to profile the Twitterers
3. Identification of the most prolific twitter users through: 
  a. Message Volume
  b. Message retweet volume 
  c. Categorization of twitter accounts 
  d. Visualizing distribution of tweets 
4. Timeline analysis of covid related tweets 
5. Message uniqueness analysis to account for duplication through Simhash 
