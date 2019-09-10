# SPAM

## Abstract 

The word “spam” is defined as an irrelevant or inappropriate message sent on the internet to a large number of recipients. Throughout my time of using social media, one of the most annoying and frightening things of the internet is spam. To most, spam is very obvious to detect. However, there are many people that fall victim to links provided in spam messages, tweets and emails. The problem I break down in this project is exploring the percentage of spam tweets on Twitter, a social media app used by millions of people worldwide. 

## Objective 

This project aims to explore the percentage of tweets that are considered spam per day, on the social media application “Twitter”. 

## Motivation 

### What is the problem that motivates you to build this product?
The purpose of this program is to explore the percentage of spam tweets created in a day. Spam is a security issue that is not emphasized due to the large amount of legitimate data covering it up on a minute-by-minute basis. Spam can manipulate the user in many forms such as money scams and revenge porn cases to a random, unintentional messages to all of your followers. 
### Why is this problem important to be addressed?  
In exploring the legitimacy of data that is put out to the public, we can determine whether spam can be considered a “security breach” or should stay neglected as a simple “low-risk”, “low-priority” error that many applications encounter. 
### Who are the users of the product?
This project addresses users who regularly use Twitter as their main platform of social media. As they are the target audience that would be heavily affected by spam tweets.
### What is the expected outcome and the utility of the product?
The expected outcome of this program would be to provide factual evidence that spam tweets are a large percentage of tweets that are put out on a daily basis. On that hypothesis, the program’s function can be shown to the company Twitter, in which they can make this issue a larger priority. As a result, they could place a strong emphasis on reducing the number of spam tweets that exist on Twitter. This, in effect, will strengthen the security and safety of the platform as a whole for users.  

## Prior Work
Adil Mouhajid wrote an article on text mining using a Twitter streaming API and Python. Text mining in this context is described as an application of natural language analytical methods and processing techniques to retrieve relevant information (Moujahid 2014). In his article, he uses this method to determine the popularity of Python, Java and Ruby by retrieving data on tweets associated with links to programming tutorials. His method of retrieving the data would be similar to mine, as I would use the same API to access data. The difference is the type of data I would be retrieving. Based on research and previous examples of spam tweets shown in news articles, I would search for specific key words that are common among spam tweets. Furthermore, I would also take a look at the profile information that is common in spam accounts. In comparison to my goal, Mouhajid’s aim is a bit toy. As he would use that data for personal gain or to fulfill a certain curiosity. However, my aim goes beyond myself, as this type of information is beneficial for the global community and the company, as it creates awareness of the continuous security issue that has not yet been fully resolved. 

## Input/Output and Proposed Solutions

### Source of the Tweet
Describes where the tweet was posted from, examples include: twitter browser, Iphone, android or a specific website.
### Time of created Tweet
Defines the exact date and time in which the tweet was posted out to the public.
### Text of Tweet
Description of the tweet itself, in text format.
### Account Name of Tweeter
Provides the name of the account that posted the respective tweet.
### Profile Information of Tweeted Account
This information describes information such as whether the account has a background image, a website URL, a profile image, number of accounts that this profile follows, number of accounts that tweeted account follows and etc.  
### Tweet Information
This information deduces whether the tweet was favorited (liked), or retweeted (reposted) by other accounts and provides an integer value.

