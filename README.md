# Sentiment-Analysis-with-scikit-learn

 Performing Sentiment Analysis using Machine Learning models with scikit-learn.

 # Introduction: 

  In this project, the main objectives are:

 • Build and employ a logistic regression classifier using scikit-learn.
 
 • Clean and pre-process text data.
 
 • Perform feature extraction with nltk
 
 • Tune model hyperparameters and evaluate model accuracy


# Features: 
bag of 1-grams with TF-IDF values:

Extremely sparse feature matrix - close to 97% are zeros

# Model: Logistic regression

𝑝(𝑦=1|𝑥)=𝜎(𝑤𝑇𝑥)

Linear classification model

Can handle sparse data

Fast to train

Weights can be interpreted

![](https://i.imgur.com/VieM41f.png)

# Dataset:

It contains the following:
 
 • IMDB movie reviews dataset

 • Contains 25000 positive and 25000 negative reviews

• Contains at most reviews per movie

• At least 7 stars out of 10  →  positive (label = 1)

• At most 4 stars out of 10  →  negative (label = 0)

• 50/50 train/test split

• Evaluation accuracy

# Model Accuracy

In this final task, we take a look at the best parameter settings, cross-validation score, and how well our model classifies the sentiments of reviews it has never seen before from the test set.
