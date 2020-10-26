# IMB-Watson-Recommendation
## Table of Contents
1. [Installation](#Installation)
2. [Project Motivation](#Motivation)
3. [File Descriptions](#Descriptions)
4. [Results](#Results)
5. [Acknowledgements](#Acknowledgements)

# Installation <a name="Installation"></a>
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

# Project Motivation <a name='Motivation'></a>

For this project the interactions that users have with articles on the IBM Watson Studio platform was analyzed and recommendation engine was created to suggest new articles to them.


# File Descriptions <a name="Descriptions"></a>
###articles_community.csv - This file contains the description for each of the articles
and user_item_interactions.csv contains the user article interactions information

###Recommendations_with_IBM.pynb - The notebook contains the project that is been divided into following tasks:
I. Exploratory Data Analysis
II. Rank Based Recommendations
III. User-User Based Collaborative Filtering
IV. Content Based Recommendations
V. Matrix Factorization

# Results <a name='Results'></a>

I. Exploratory Data Analysis

Before making recommendations of any kind, the data exploration was performed. 

II. Rank Based Recommendations

The most popular articles simply based on the most interactions was identified. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users

IV. Content Based Recommendations

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using NLP, a content based recommendation system was created. 

V. Matrix Factorization

Using the user-item interactions, a matrix decomposition was created. This decomposition, will give an idea of how well prediction of new articles an individual might interact with can be made

# Acknowledgements <a name='Acknowledgements'></a>

1. Udacity for providing such a complete Data Science Nanodegree Program
2. IBM for providing the datasets
