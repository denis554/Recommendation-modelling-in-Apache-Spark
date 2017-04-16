

# Recommendation-modelling-in-Apache-Spark
## Ongoing work : To be completed by 26th of April

## Task
Using collaborative filtering model (ALS) implemented in Apache Spark to recommend movies based on ratings given by similar users.

## 1- Choose the Dataset and Explain the reasons

### Dataset
The Movielens dataset will be used for this task (https://grouplens.org/datasets/movielens/). 
GroupLens Research has collected and made available rating data sets from the MovieLens web site (http://movielens.org). The data sets were collected over various periods of time, depending on the size of the set.

* Small dataset: 100,000 ratings and 1,300 tag applications applied to 9,000 movies by 700 users.
* Full dataset: 24,000,000 ratings and 670,000 tag applications applied to 40,000 movies by 260,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags.


## 2- Choose the task and Explain the reasons

"Recommendation Algorithms"

Collaborative filtering algorithms will be used.

Idea: If a person A likes item 1, 2, 3 and B like 2,3,4 then they have similar interests and A should like item 4 and B should like item 1.

This algorithm is entirely based on the past behavior and not on the context. This makes it one of the most commonly used algorithm as it is not dependent on any additional information. For instance: product recommendations by e-commerce player like Amazon and merchant recommendations by banks like American Express. https://www.analyticsvidhya.com/blog/2016/06/quick-guide-build-recommendation-engine-python/

Further, the two types of collaborative filtering algorithms considered are :

#### User-User Collaborative filtering  OR  Item-Item Collaborative filtering. 


## 3- Separate the data for Training, Validation and Testing

Training (70%);
Validation (15%);
Testing (15%);


## 4- Implement a grid search with "pyspark.ml.tuning.ParamGridBuilder[source]" of the following Parameters
At least:
#### a)  One Feature Preprocessing Step: [Name] [Coef.] 
#### b)  One Machine Learning Parameter: [Name] [Coef.]
#### c)  One Training set Size: [Name] [Coef.]


## 5- Measure the Performance with "pyspark.ml.tuning.TrainValidationSplit" and Document it and Time taken for:

#### a) Training and validating
#### b) Test




