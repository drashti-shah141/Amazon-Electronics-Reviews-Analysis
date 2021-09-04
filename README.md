# Amazon-Electronics-Reviews-Analysis
This repository contains my work on detailed analysis of Amazon's Electronics Category Product reviews, and consists of Data cleaning, Sentiment Analysis, Exploratory Analysis, Text Analysis, and various Rating Predictive Models. This was completed as part of a class group submission. All credits to be given to the owner.

## Dataset 

We used two datasets for this purpose- The first dataset has over 20 million rows of electronics products sold on Amazon dating from 1996 to 2018. The second dataset has the metadata which includes description, price, brand info, and co-purchasing links. It has over 700,000 rows dating from 1996 to 2018. Both these datasets contain information such as ratings, product title, the main category that the product belongs to, text reviews of the users, etc.

We combined both datasets for all of our analysis and predictive modeling. We narrowed our analysis for the period from 2016-2018 to check the true occurrences of fake reviews in recent years and to make the dataset more manageable for R to handle. This timeframe covers the period up to and after Amazon changed its terms to stop incentivized reviews.

Final Dataset – It represents the combined dataset statistics below:
* Number of Reviews- 8,951,484
* Number of distinct users- 5,112,945
* Number of products- 443,699
* Period of Analysis- Jan 2016 - Dec 2018
* Data Source- UCSD Amazon review data (2018), Owner- Jianmo Ni, UCSD
* Data link- http://deepyeti.ucsd.edu/jianmo/amazon/index.html

## Description of variables

The description of combined dataset is as follows:

1. reviewerID – ID of the reviewer, e.g., A2SUAM1J3GNN3B
2. asin – Amazon Standard Identification Numbers of the products, e.g., 0000013714, B01HJH6CEY
3. reviewText – Text of the review
4. overall – Rating of the product, running from 1-5, with 1 being the worst, 5 being the best
5. summary – Summary of the review, typically in a few words. Can be treated as a topic of the review
6. title – Name of the product, e.g., Desktop Dock for Samsung Galaxy Tab 4
7. main_cat – A main category of the product

## Research Questions addressed

* Can we predict the review score based on review text and verified reviews accurately?
* Is it possible to predict the review sentiments using natural language processing?
* Are there any particular trends in the review score ranging from 2016 to 2018 depicting Amazon’s efforts in combating the fake reviews?
* Are the reviews for certain products such as earphones, headsets, etc more inclined towards higher review scores and positive sentiments?
* Can we visualize any structure in words in the text reviews using sentiment analysis?
* Do verified reviews display more positive sentiments?

