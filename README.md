>## [enhanced Twitter-WeRateDogs project](https://github.com/victorlifan/projects_review/tree/master/Twitter-WeRateDogs%20project)

## Project Title
Twitter_WeRateDogs_API_Wrangle_and_Analyze_Data

## Date created
Project is created on March 6th 2020.

## Description
Tweet archive of Twitter user @dog_rates, also known as WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. Tasks in this project are as follows:
+ Data wrangling, which consists of:
  + Gathering data.
  + Assessing data
  + Cleaning data
  + Storing
+ Analyzing
+ Visualizing your wrangled data
+ Reporting on 1) data wrangling efforts and 2) data analyses and visualizations

## About
###### Gathering Data for this Project: [`Supporting Materials`](https://github.com/victorlifan/Twitter_WeRateDogs_API_Wrangle_and_Analyze_Data/tree/master/Supporting%20Materials) folder
+ `twitter-archive-enhanced-2.csv`: The WeRateDogs Twitter archive.
+ `image_predictions.tsv`: The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network.
+ `tweet_json.txt`: A json data file queried though Twitter API using Python's Tweepy library according the tweet IDs in the WeRateDogs Twitter archive.

###### Action codes: [`wrangle_act.ipynb`](https://github.com/victorlifan/Twitter_WeRateDogs_API_Wrangle_and_Analyze_Data/blob/master/wrangle_act.ipynb)
Code for gathering, assessing, cleaning, analyzing, and visualizing data.

###### Cleaned data : [`twitter_archive_master.csv`](https://github.com/victorlifan/Twitter_WeRateDogs_API_Wrangle_and_Analyze_Data/blob/master/twitter_archive_master.csv)
Wrangling result, ready to analyze data in csv file.

###### Report: [`reports`](https://github.com/victorlifan/Twitter_WeRateDogs_API_Wrangle_and_Analyze_Data/tree/master/reports)folder
+ [`Wrangle Report.pdf`](https://github.com/victorlifan/Twitter_WeRateDogs_API_Wrangle_and_Analyze_Data/blob/master/reports/Wrangle%20Report.pdf): briefly describes wrangling efforts.
+ [`Act Report.pdf`](https://github.com/victorlifan/Twitter_WeRateDogs_API_Wrangle_and_Analyze_Data/blob/master/reports/Act%20Report.pdf): communicates the insights and displays the visualization(s) produced from wrangled data.  
## Software used
+ Jupyter Notebook
+ Python 3.7
> + Pandas
> + Numpy
> + Matplotlib
> + Statsmodels
> + tweepy
> + json
> + requests
+ Google Docs
## Files used
+ `twitter-archive-enhanced-2.csv`: The WeRateDogs Twitter archive.
+ `image_predictions.tsv`: The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network.
+ `tweet_json.txt`: A json data file queried though Twitter API using Python's Tweepy library according the tweet IDs in the WeRateDogs Twitter archive.

## Credits
+ Data provided by:
    + [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)
    + Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs).
+ Instruction and assist: [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)
+ Photos: [Dog learn: Golden Retriever vs Saluki](https://www.dog-learn.com/breed-vs-breed/golden-retriever-vs-saluki/)
