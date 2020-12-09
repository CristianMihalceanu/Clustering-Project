# Classifying tennis players - Clustering Project

## Project Overview

1. Using both "The elbow method" and "The Dendrogram Approach", we were able to determine that tennis players can roughly be categorized in 4 different clusters
2. We created 4 dataframes from the original data, each row representing the performance of a player during a match
3. Gathered a better understanding of the data through EDA
4. Applied PCA to visualize the data in 2D
5. Interpreted the results given by the clustering algorithm

 ## Code & Resources used
 
 1. Python version 3.7
 2. Packages: numpy, pandas, seaborn, matplotlib, sklearn
 3. Udemy link: [Data Science](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/)
 4. Youtube links: [link1](https://www.youtube.com/watch?v=vtuH4VRq1AU&t=263s) 
 
 ## Data - A better understanding
 
Data collected from UCI machine learning repository
 
1. Result Result of the match (0/1) 

2. FSP = First Serve Percentage for player  (Real Number)

3. FSW = First Serve Won by player  (Real Number)

4. SSP = Second Serve Percentage for player  (Real Number)

SSW = Second Serve Won by player (Real Number)

ACE = Aces won by player  (Numeric-Integer)

DBF = Double Faults committed by player  (Numeric-Integer)

WNR = Winners earned by player  (Numeric)

UFE = Unforced Errors committed by player  (Numeric)

BPC = Break Points Created by player  (Numeric)

BPW = Break Points Won by player  (Numeric)

NPA = Net Points Attempted by player  (Numeric)

NPW = Net Points Won by player  (Numeric)
 
 ## Feature Generation
 
 1. Transformed "Time" column into a datetime object so that we can call attributes off of the elements.
 2. We added another columns consisting of the lengths of the messages
 3. Dropped columns which were no longer useful
 4. Checked if there were any blank texts
 
 ## EDA
 
 A sneak peak from inside the project:
 
 ![alt text](https://github.com/CristianMihalceanu/NLP-Project/blob/main/length.PNG)
 
 ![alt text](https://github.com/CristianMihalceanu/NLP-Project/blob/main/wordcloud.PNG)
 
 ## Text Generation
 
 1. Provided a brief explanation of RNN and LSTM
 2. Created a neural network and used backpropagation to train it on our data in order to generate a new word based off of 50 previous ones
 
 ## Model Performance 
 
 Our model for predicting whether a person suffers from depression achieved 75% accuracy
 
 ## Future Work
 
 Following the result of the algorithm, an individual should be adviced to visit a professional psychologist or be provided a chatbot.
 
