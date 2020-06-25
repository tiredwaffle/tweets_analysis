# Analysis of Twitter users' posts related to Coronavirus: Analysis of time series of mention of proper names

This is university project for the Text Mining Course.

In the last few months, a pandemic of the new COVID-19 virus has swept the world. With the closure of cinemas, shops, malls, all human communication moved to the Internet. All discussions and debates swept through social networks: Twitter, Facebook, Instagram, and Vkontakte were flooded with daily reports of deaths or new cases, theories about the origin of the virus, or hopes for a quick end of the quarantine.
In this project, 5,000 tweets related to the coronavirus between March 1 and May 1, 2020, were removed for analysis.
Social networks have always been and remain indicators of user mood. For example, in the United States, studies have found a correlation between the analysis of tweets in a particular region and the crime rate. Our task is not so massive. Trying to  analyze in general tweets of the Ukrainian-language segment of Twitter on the topic of coronavirus, to analyze the time series of mentioning of certain countries, organizations or people and to understand their dynamics.

Twitter is a social network of microblogs that allows users to send short text messages (up to 280 characters) using SMS, instant messaging services and third-party client programs. Twitter has 330 million active users per month and 145 million daily Twitter users. That is, about 42% of Twitter users use the platform every day.

The GetOldTweets3 library was used to collect data from the Twitter social network. GetOldTweets3 is an improvement on a branch of Jefferson Henrik's original GetOldTweets-python. The official Twitter API has a limited time limit, and it is often impossible to get tweets older than a week. Some tools provide access to old tweets, but most of them are paid. This library works directly by simulating the scrolling of a Twitter page, collecting data in JSON. The result is an advantage in being able to find the deepest old tweets. It also includes features such as retweet counting, searching multiple user accounts, etc., which allows you to specify the request.

Currently, only ukrainian version of the project is available in the proper form. Though I am working on transforming it into article in english.
