
# IMDB-Movie-Reviews-TextClassification

## Project Description

This is a Deep Learning based approach to determine whether a movie the review is positive or negative using theIMDB movie review sentiment classification dataset. The kernel imports the IMDB reviews (originally text - already transformed by K…


This notebook is part of my deep learning DAAN 570 class, I used a AWS sagemaker instance for multi GPU runtime training and S3 for initial storage.


## Dataset 

This is a dataset of 25,000 movies reviews from IMDB, labeled by sentiment
  (positive/negative). Reviews have been preprocessed, and each review is
  encoded as a list of word indexes (integers).

## Sources:

* IMDB sentiment classification dataset : https://github.com/keras-team/keras/blob/master/keras/datasets/imdb.py
