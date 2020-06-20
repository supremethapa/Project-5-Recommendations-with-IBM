# Recommendations_with_IBM

# Introduction

For this project, I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and made recommendations to them about new articles they will like. 

In order to determine which articles to show to each user, I performed a study of the data available on the IBM Watson Studio platform.  

The project is divided into the following tasks:

# 1) Exploratory Data Analysis

Before making recommendations of any kind, you will need to explore the data you are working with for the project. This space is used to explore, before diving into the details of our recommendation system in the later sections. 

# 2) Rank Based Recommendations

To get started in building recommendations, we found the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users.

# 3) User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, I looked at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

# 4) Content Based Recommendations (Optional)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using NLP, we might come up with some extremely creative ways to develop a content based recommendation system. 

# 5) Matrix Factorization

Finally, a machine learning approach is taken to give recommendations. Using the user-item interactions, I built a matrix decomposition. Using the decomposition, I got an idea of how well you can predict new articles an individual might interact with. Finally, I discussed which methods could we use moving forward, and how we might test how well the recommendations are working for engaging users.
