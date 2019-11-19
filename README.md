# Recommendation-Systems-With-IBM

## Introduction

For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, 
and make recommendations to them about new articles I think they will like.

## Motivation

From the data provided to me from IBM Watson, I could divided my project into following tasks:

### I. Exploratory Data Analysis

Before making recommendations of any kind, I need to explore the data I am working with for the project. 
So I Dived in to see what I can find. There are some basics I need to know to be familiar with the data.

### II. Rank Based Recommendations

To get started in building recommendations, I first found the most popular articles simply based on the most interactions. 
Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. 
These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items
they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards
more personal recommendations for the users. 


### IV. Matrix Factorization

Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, 
I built out a matrix decomposition. Using my decomposition, I got an idea of how well I can predict new articles
an individual might interact with (spoiler alert - it isn't great). I finally discussed which methods I might use moving forward, 
and how I might test how well my recommendations are working for engaging users.

