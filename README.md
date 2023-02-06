# Bloc N° 3 : Analyse prédictive de données structurées par l'intelligence artificielle.

[Video explain - Bloc 3](https://share.vidyard.com/watch/RE68BWh7mr8Re4x536p74N?)


# 1- Walmart Project

## Context and goals of this study:

Walmart's marketing service is looking for a machine learning model able to estimate the weekly sales in their stores, with the best precision possible on the predictions made. 

Supervised Machine learning will be used in this project. The target variable is quantitative, thus it is a regression will be used.

The applied model here is a linear regression model.


## Available files :

-	Walmart_FINAL.ipynb : notebook containing machine learning
-	Walmart_Store_sales.csv : data source



# 2- Conversion rate challenge

## Context and goals of this study:

Let's participate to a machine learning competition through this project!

- A labelled dataset has been received; this file is used to train the model: make the train/test split, preprocessings, assess performances, try different models, fine-tune hyperparameters.

- An unlabelled dataset has been also received: it will be computed together with the train dataset to make predictions that will be dumped to a csv, and will be used by the organiser of the challenge to assess the model.

This project is about predicting  the behaviour of the users visiting their website: the machine learning model should predict if a given user will subscribe to the newsletter.

This is a classification model, and F1 score will be used to assess the model.

## Available files :
-	Conversion_rate_challenge_FINAL.ipynb : notebook containing machine learning
-	conversion_data_train.csv : data source containing labels
-	conversion_data_test.csv : data source containing non labelled data
-	conversion_data_test_predictions_ElisaV5.csv : predictions based on XGBoost model, trained on both ‘conversion_data_train.csv’ and ‘conversion_data_test.csv’


# 3- Uber pickups
## Context and goals of this study:

Uber is a ride-sharing application for people who cannot afford a taxi.

Sometimes drivers are not around when users need them. Uber would like to upgrade their app to recommend hot-zones in major cities to be in at any given time of day.

This project is limited to the New York area, and set on data received related to April 2014.

The goal of this project is to define clusters defining the best place to be for Uber drivers. 

To do so, unsupervised machine learning will be used as 

- there is no target variable and data are not labelled

- the goal is to create consistent grouping of the data.

## Available files :
- Uber_FINAL.ipynb : notebook containing machine learning
- uber-raw-data-apr14.csv : data source


Happy reading !

