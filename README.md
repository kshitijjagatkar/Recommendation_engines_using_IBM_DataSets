# Recommendation_engines_using_IBM_DataSets
For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and made recommendations to them about new articles I think they will like.

1. Project Motivation
2. Project Summary
3. Project Components
4. File Descriptions
6. Installation & Run
7. Results

## 1. Project Motivation
 I recently gained some knowladge about building recommendation engines So, I found out this project can help me build an overall intution about recommendation engines.
 I applied these skills to analyze IBM Watson Studio articles data to build & understands things behind the recommendations.

## 2. Project Summary
 So, This projects has some major components listed as follows which I followed throughout the notebook to guid myself & as well you. I will be performing some EDA first
 then some standard recommendation methods & finally a machine learning approach to make recommendation.
 
## 3. Project Components
This project basically divided into sections as follows:

I. Exploratory Data Analysis

Before making recommendations of any kind, will need to explore the data, Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook.

II. Rank Based Recommendations

To get started in building recommendations, first we will find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

IV. Matrix Factorization

Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition.

## 4. File Structure & Description
* Data

  | - articles_community.csv
    - user-item-interactions.csv
  
  | - Recommendations_with_IBM.ipynb
  
  *Data : this folder has all data
  
  *Other files : There is main notebook file named "Recommendations_with_IBM.ipynb" which has all the code & rest files are needed while working.
  
  *README.md : this files has all description of the project.
  

## 5. Installation & Run
 
 This project doesn't need any extra installation if you have anaconda distribution installed.
