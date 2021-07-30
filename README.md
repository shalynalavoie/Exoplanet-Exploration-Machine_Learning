# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)


## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

In this homework assignment, you will need to:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

## Instructions

### Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

### Analysis
Model 1
Training Data Score: 0.8455082967766546
Testing Data Score: 0.8415331807780321

Model 2
Training Data Score: 0.8922372687392714
Testing Data Score: 0.8884439359267735

In looking at the two models, model 2 had a higher training and test score. We can see that the KNN model used produced a more accurate prediction. I believe more models would have to be tested to make a decision of which to use for potentially predicting new exoplanets. In selecting specific features this may improve the models prediction for next time. 


