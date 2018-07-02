**##Cryptocurrency Analysis**

This repository contains the codes and files pertaining to sentiment analysis and comparison of various top cryptocurrencies today.

**INTRODUCTION**

A cryptocurrency is a digital or virtual currency that uses cryptography to secure financial
transactions, control the creation of additional units, and verify the transfer of assets.
Cryptocurrencies use decentralized control as opposed to centralized electronic money
and central banking systems. The first cryptocurrency to capture the public imagination
was Bitcoin, which was launched in 2009. As of June 2018, there are over 17 million
bitcoins in circulation with a total market value of over $140 billion. Bitcoin's success has
spawned several competing cryptocurrencies, such as Litecoin, Ripple and Ethereum.


**MOTIVATION FOR THE STUDY**

While there are multiple analyses that have been performed on cryptocurrencies
since the time of their inception, for this particular case I wanted to find the
correlation between the various top rated cryptocurrencies today. The case study
also focuses on the sentiments that drive the market of these cryptocurrencies. Today data
related to these is freely available through various social media sites like Twitter as well
as through various other API's.



**QUESTIONS & HYPOTHESIS**

Following are some of the key questions/ hypothesis that I would like to answer
a)	What is the trend/ distribution that cryptocurrency prices are following? How have these fared over the past year?
b)	Comparison of prices of major cryptocurrencies.
c)	How does the price of one cryptocurrency effect the others?
d)	What is the correlation between the major cryptocurrencies?
e)	What are the sentiments of the various stakeholders regarding cryptocurrencies?


**DATA COLLECTION & CLEANING**

Twitter, Google Trends and CryptoCompare were predominantly used as data source for
this study.
a) Using various hashtags, data was downloaded from Twitter for a time period of
approximately one year.
b) Collect data for different cryptocurrencies like Bitcoin, Ethereum, Ripple and Litecoin
from https://min-api.cryptocompare.com/ using their API.
c) Using 'Cryptocurrency' as search term in https://trends.google.com/trends/ , download
interest data for the period from June 2017 to June 2018.
d) Download data on “Related topics” and “Related queries” as well for the same
“Cryptocurrency” search term to get possible keywords.

The study proceeds in 2 parts:
1.	The data collected from cryptocompare is used for comparison of closing prices of various cryptocurrencies today. Various visualizations and plots are used to analyse the trends over the past year. Further we can visualize the correlation between four major cyptocurrencies.

2.	The second part is mainly related to sentiment analysis of data collected from twitter. Data is collected on the basis of popular hashtags and then sentiment is analysed with the help of various visualizations. The tweets are tokenized to find the most common words used and a wordcloud is generated.
