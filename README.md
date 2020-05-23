# nlp-predicting-tags-stackoverflow
How to predict tags for posts from StackOverflow? To solve this task you will use multilabel classification approach.
- Week 1 of Natural Language Processing Course

## Problem

- Considering the task of predicting tags for posts from StackOverflow.  
- To solve this task you will use multilabel classification approach with bag of words model, with tf-idf features.
- For MultiClass Classification we use One vs Rest Classifier with Logistic Regression


## Libraries

In this task you will need the following libraries:

- Numpy — a package for scientific computing.
- Pandas — a library providing high-performance, easy-to-use data structures and data analysis tools for the Python
- scikit-learn — a tool for data mining and data analysis.
- NLTK — a platform to work with natural language.

## Datasets

In this task you will deal with a dataset of post titles from StackOverflow. You are provided a split to 3 sets: train, validation and test. All corpora (except for test) contain titles of the posts and corresponding tags (100 tags are available). The test set is provided for Coursera's grading and doesn't contain answers

## Results and Conclusions

- We evaluated each model with F1 weighted score, and submitted on coursera platform. 
- The best model had f1-score = 0.65 and passed on coursera evaluation.
