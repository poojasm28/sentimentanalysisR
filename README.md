# sentimentanalysisR

Sentiment Analysis on Amazon, IMDb and Yelp Reviews using Naïve Bayes algorithm in R

INTRODUCTION

The most important information any company selling a product or service needs is whether their customers like or dislike their product or service. It is critical for every company to understand what customers think and feel about their service and product so that they can continuously evolve and meet the demands of a consumer in a more wholesome way. With the gamut of products and services available these days, if a company wants to be relevant and not lose a customer; it is extremely prudent for them to listen to what customers think of the brand and address the issues they face. With the advent of online markets that sell products and deliver services at the click of a button, it becomes even more essential to understand how a product or service is received by a customer since there is no physical interaction with a customer. However, unlike traditional marketing where information on how the product or service was received had to be made available by spending tones of money on conducting surveys; online markets provide real time and easy feedback from customers in the form of reviews. 

THE NEED FOR CONDUCTING SENTIMENT ANALYSIS

Sentiment Analysis is the process of computationally identifying and categorizing opinions expressed in any text to determine whether the writers attitude toward a topic, product etc. is positive, negative, or neutral. Conducting sentiment analysis has several benefits. From the managerial perspective, social media/ digital media is not just a platform where you can post and promote your services. It is a place where your customers talk about your brand and is full of information about how brand is being perceived by your target customers. The information you get from sentiment analysis provides you with means to optimize your marketing strategy. By listening to what your customers feel and think about your brand, you can adjust your high-level messaging to meet their needs. It helps you complete your market research by getting to know what your customers' opinions are about your products/services and how you can align your products/services with what the consumer needs. Another important role of sentiment analysis is that it can give you real time negative feedback that you can pick up on and work towards resolving. The faster you react to a complain the better it is for a brand. Thus, sentiment analysis is an extremely important tool for companies looking to grow and become profitable in the current market.

ABOUT THIS PROJECT

In this project, sentiment analysis will be conducted on reviews from three major digital platforms – Amazon, IMDb & Yelp. Amazon is an electronic commerce and cloud computing company and is the biggest online retailer. IMDb also known as Internet Movie Database, is an online database of information related to world films, television programs, home videos and video games, and internet streams, including cast, production crew and personnel biographies, plot summaries, trivia, and fan reviews and ratings. Yelp develops, hosts and markets Yelp.com and the Yelp mobile app, which publish crowd-sourced reviews about local businesses, as well as the online reservation service Yelp Reservations. The reviews i.e. the opinions will be categorized as positive or negative to identify the reviewers attitude towards a product or service.

INFORMATION ABOUT THE DATASET

The Sentiment Labelled Sentences Data Set was created for the Paper 'From Group to Individual Labels using Deep Features', Kotzias et. al. KDD 2015.  The sentences come from three websites: imdb.com, amazon.com and yelp.com and contain positive and negative reviews. For each website there are 500 positive and 500 negative comments that are randomly selected from larger datasets of reviews. Only sentences with a clear positive or negative connotation are selected with the goal of not including any neutral sentences.
The Amazon dataset contains reviews for products in the cell phones and accessories category that are sold on amazon.com. The reviews are scored, and the scores are on a scale from 1 to 5. A score of 4 and 5 will be considered positive and scores of 1 and 2 will be considered negative. 
The IMDb dataset contains movie reviews posted on imbd.com and have a binary sentiment label, either positive or negative. 
The Yelp dataset contains restaurant reviews posted on yelp.com. The reviews are scored on a scale of 1 to 5. A score of 4 and 5 will be considered positive and a score of 1 and 2 will be considered negative. 

ALGORITHM

As part of the project, Naïve Bayes algorithm will be used on all three datasets to classify if a review is positive or negative.  Also, as part of the investigation on the dataset, a word cloud will be created to recognize the high frequency words used in both the positive and negative connotations. 

DOWNLOADING THE DATASET

The data has been downloaded from https://www.kaggle.com/marklvl/sentiment-labelled-sentences-data-set/data and was created from the Paper 'From Group to Individual Labels using Deep Features', Kotzias et. al. KDD 2015. 
