# Recommendations-with-IBM

For this project I am analysing the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will probably like.

In order to determine which articles to show to each user, I will be performing a study of the data available on the IBM Watson Studio platform.

##The project is divided into the following tasks:  
I. Exploratory Data Analysis  
Before making recommendations of any kind, I explore the data for the project, before I dive into the details of the recommendation system in the later sections.

II. Rank Based Recommendations
To get started in building recommendations, I will first find the most popular articles simply based on the most interactions.

III. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, I will look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

IV. Matrix Factorization
Finally, I complete a machine learning approach to building recommendations. Using the user-item interactions, I build out a matrix decomposition. Using the decomposition, we will get an idea of how well we can predict new articles an individual might interact with (spoiler alert - it isn't great).

##Used libraries
- pandas
- numpy
- matplotlib.pyplot
- pickle
- os
