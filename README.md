# Data_Wrangling (*Work in progress*)
Introduction

The goal of the project is conduct data analysis and visualisation by wrangling data from Twitter user ’WeRateDogs’. With Twitter archive in hand, the objective is to gather comprehensive data to supplement the archive, which contains basic tweet information, to begin and complete data analysis on the data. The data will be assessed on its tidiness and quality and cleaned effectively before developing a visual.

The task began with obtaining further data by querying the Twitter API, which was then imported to Jupyter notebook for assessment. The data in hand contains basic information and to get a complete picture of data from WeRateDogs, one could be sourced out Twitter API based on the Tweet IDs which are already present in the archive. The data is in the csv format.
The idea is to gain access to the API by registering a developer account with Twitter and subsequently obtained their access code. This will create an API object that you can use to gather Twitter data. The data obtained here was saved in JSON format, of which extraction was done via Tweepy.

For this project, there is a neural network from Udacity showcasing tweet image predictions and data therein is on its server, which was downloaded programmatically using Requests.
All data obtained here was amalgamated for an easy review.

References:

https://www.tutorialspoint.com/python_pandas/python_pandas_series.htm

https://twython.readthedocs.io/en/latest/

https://stackoverflow.com/questions/28384588/twitter-api-get-tweets-with-specific-id

https://wiki.python.org/moin/HandlingExceptions

http://docs.tweepy.org/en/v3.8.0/api.html

https://stackoverflow.com/questions/21308762/avoid-twitter-api-limitation-with-tweepy

https://www.marsja.se/how-to-read-and-write-json-files-using-python-and-pandas/
