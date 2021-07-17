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
* app

  | - template
  
  | |- base.html  #my-dashboard's base page
  
  | |- home.html #my-dashbord's welcome page
  
  | |- master.html # main page of web app
  
  | |- go.html # classification result page of web app
  
  |- run.py # Flask file that runs app

* data

  |- disaster_categories.csv # data to process
  
  |- disaster_messages.csv # data to process
  
  |- process_data.py
  
  |- disaster_response.db # database to save clean data to
  
* models
 
  |- train_classifier.py
  
  |- trained_model.pkl # saved model
  
  README.md
  
1. Data Directory
      * This folder contains "process_data.py" which has all ETL code and perform pipeline tasks which takes input files "message.csv" &
        "categories.csv" produces database file for our model.
2. Model Directory
      * This folder has "train_classifier.py" which takes database file perform ML pipeline and produces pickle file to use it in our flask app.
4. App directory
      * this folder contains web page code. "run.py" takes care of running server & all our code. upper folders are templetes and static which contain html 
        & css, java files   respectively.

## 5. Installation & Run

