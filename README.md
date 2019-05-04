<!-- GFM-TOC -->
* [MovieRecommendation](#MovieRecommendation)
    * [Introduction](##Introduction)
    * [PartI](##PartI)
    * [PartII](##PartII)
    * [PartIII](##PartIII)    
    
    
# MovieRecommendation
## Introduction
* Design and implement the Movie Recommendation System based on MovieLens Datasets, and evaluate the accuracy and efficiency of our recommendation model
* Analyze the dataset of movie comments by using NLP methods, and exact useful comment keywords for a specific movie
* According to the NLP result, we will generate the subjective tags for every movie, like "good", "boring", "suck" and so on, which will help clients to find their interests
## PartI
### NLP for Movie comments
* Select the most frequency words in the comments
## PartII
### Collaborative Filtering
* Collaborative filtering is a method of making automatic predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating).
* What we should do to use Collaborative Filtering Algorithm?
  * We should make data cleansing
  * We should converse the datas
  * We should generate the basic matrix for counting the interactions between users and items
  * We should calculate the similarity of users or items, then generate similaritry matrix
  * According to the similarity of matrix, we can generate the final recommendation lists
## PartIII
### Tensorflow Movie Recommendation
