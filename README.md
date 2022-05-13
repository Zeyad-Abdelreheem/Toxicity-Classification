# Toxicity_Classification

This repo is about creating a simple comment toxicity classifier
(based on this tutorial [1])

### The expected output is
<img src="test.png" alt="out" title="toxicity classifier">


## The Outline
### 1- Collect the dataset
### 2- Clean and preprocess the dataset
### 3- Create the model
### 4- Train the model
### 5- Evaluate the model
### 6- Deploy the model in the app
### 7- Resources
------------------------------------------------------------------------

The data was downloaded from kaggle [2]

all related details untill step 5 can be found in train.ipynb 


definitely this is not a perfect classifier (there is no perfect one).

but it can get analyze comments with accuracy between 80 to 90 %

to improve these results :-
- More dataset is needed as there are a lot of neutral comments that make the model slightly biased 
- Some tuning is needed to handle bias - variance trade off


## Resources :-
##### [1] Nicholas renotte youtube channel : https://www.youtube.com/watch?v=ZUqB-luawZg
##### [2] Kaggle dataset : https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data

