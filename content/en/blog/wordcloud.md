---
title: "Word Cloud Analysis to Capture Passengers Concern using Twitter Data"
date: 2020-05-17
tags: ["wordcloud", "passengers", "challenges","service","airline"]
---

Airline industry is facing humongous challenges due to the Covid-19.

Over all over 8000 Cr. has been stuck due to lockdown. The passengers money is stuck and the refund issues are in the form of credit shells or in the agent's wallet without the consent of the passengers. 

The credit shell has a expiry date and a restriction to use it only on the same passengers. However,many would not travel with in the stipulated time given by the airlines which leads to loss to the passengers.

In these testing times, the whole airline industry has suffered and it also has blocked enormous amount of passengers money ranging from few thousands to lakhs of rupees. 

The analysis of passengers concerns is done on sample twitter data set as follows.

Steps used to analyse the twitter data (Through the Twitter API Code).

- Search Twitter using _makemytrip_ as keyword.
- Retrieve the data and store in filesystem.
- Clean the content
- Create word cloud for the content retrieved.

The following word count is obtained by analyzing the tweets, the tweets used are in the range of thousands.

 ![Word Cloud on MakeMyTrip](/img/wordcloudmmt1.png)

It is evident from the word cloud that

- Passengers are demanding refund.
- They are trying to reach out to Deep Kalra, CEO of MakeMyTrip.
- They are complaining to DGCA and other authorities to find a way to get back their hard earned money.

There are various news articles on this issue, however, no one has put forth  point of view using the twitter data set which represents the public sentiment. This could have added value to the news article.

##### **References:**

Word Cloud is formed using [TagCrowd](https://tagcrowd.com/) 

