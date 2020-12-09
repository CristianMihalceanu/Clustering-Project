# Classifying tennis players - Clustering Project

## Project Overview

1. Using both "The elbow method" and "The Dendrogram Approach", we were able to determine that tennis players can roughly be categorized in 4 different clusters, which is useful for developing a winning stategy against an opponent, provided we know which cluster he/she belongs to
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
 
Result Result of the match (0/1) 

FSP = First Serve Percentage for player  (Real Number)

FSW = First Serve Won by player  (Real Number)

SSP = Second Serve Percentage for player  (Real Number)

SSW = Second Serve Won by player (Real Number)

ACE = Aces won by player  (Numeric-Integer)

DBF = Double Faults committed by player  (Numeric-Integer)

WNR = Winners earned by player  (Numeric)

UFE = Unforced Errors committed by player  (Numeric)

BPC = Break Points Created by player  (Numeric)

BPW = Break Points Won by player  (Numeric)

NPA = Net Points Attempted by player  (Numeric)

NPW = Net Points Won by player  (Numeric)
 
 ## Data Preprocessing
 
 1. Concatenated the dataframes together
 2. Renamed the columns 
 3. Changed row indices

 ## EDA
 
 A sneak peak from inside the project:
 
 ![alt text](https://github.com/CristianMihalceanu/Clustering-Project/blob/main/corr.PNG)
 
 ![alt text](https://github.com/CristianMihalceanu/Clustering-Project/blob/main/linear%20dependence.PNG)
 
  ![alt text](https://github.com/CristianMihalceanu/Clustering-Project/blob/main/pca%20result.PNG)

 
 ## Model Building
 
 1. Applied "The elbow method" and "The Dendrogram Approach"
 2. Implemented KMeans algorithm which provided us with the data separated in 4 clusters
 3. We later interpreted the results to develop stategies for future games
 
 
 ## Future Work
 
 Following the result of the algorithm, a strategy should be put together alongside the coach in order to develop a winning system against players fom each of the clusters
 
