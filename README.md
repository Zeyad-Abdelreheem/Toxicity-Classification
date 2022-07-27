# Toxicity-Classification

This repo is about creating a simple comment toxicity classifier which is a model that takes a comment and outputs the probability of that comment being toxic (carry negative thoughts).
(based on this [tutorial](https://www.youtube.com/watch?v=ZUqB-luawZg) )

### The expected output is
<img src="test.png" alt="out" title="toxicity classifier">


## Steps
#### 1- Collect the dataset
#### 2- Clean and preprocess the dataset
#### 3- Create the model
#### 4- Train the model
#### 5- Evaluate the model
#### 6- Deploy the model in the app
------------------------------------------------------------------------

The [data](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data) was downloaded from kaggle

definitely this is not a perfect classifier (there is no perfect one).

but it can get analyze comments with accuracy between 80 to 90 %

to improve these results :-
- More dataset is needed as there are a lot of neutral comments that make the model slightly biased 
- Some tuning is needed to handle bias - variance trade off
- Transfer learning can be used by using BERT for a better text encoding



### Prerequisites

You need to install all the following libraries to run the notebook correctly so if any library is missing, just use its corresponding command 
```
pip install tensorflow
pip install tkinter
pip install numpy 
pip install os
pip install pandas
```


## Testing
- Open test_app.ipynb
- Run the notebook
- Enter your sentence in the window that showed up
- Hit analyze

## Built With

* [Tensorflow](https://www.tensorflow.org/) 
* [Keras](https://keras.io/) 
* [Python](https://www.python.org/)

## Authors

* **Zeyad Abdelreheem** [LinkedIn](https://www.linkedin.com/in/zeyad-omar/)
