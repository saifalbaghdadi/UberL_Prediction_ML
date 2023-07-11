# UBER RIDES PREDICTION USING MACHINE LEARNING:

As ride-hailing services become more popular, being able to reliably estimate demand can help operators allocate drivers to clients more efficiently, reducing idle time, improving traffic congestion, and improving the passenger experience.
We making a Flask based web application that will predict the Number of Weekly Rides using machine learning model.

## For making this Appliation we mainly divide the project in two steps:
* Training Model
* Deploy the trained model In the Flask app

## Library Requirement:
* Flask
* numpy
* scikit-learn
* pandas
* pickle

For Model Traning, we import some necessary libraries. Read the dataset using the pandas library. after reading the dataset we generally divide the dataset into training and test split by using sklearn train_test_split.

Then trained a most popular machine learning model name Linear regression. Basically for uber ride prediction, the target labels Number of weekly riders are continuous values. So we need a regression-based model to predict the unknown outcomes.

After training the linear regression model we save the trained model in a pickle file.

After training a model. It’s time to make the complete user-friendly web application to test our trained model. First, we import some necessary libraries then load the model using pickle again. We make a prediction function that takes input from the user and predicts the output

## Outputs:
<img align="center" alt="PNG" src="https://raw.githubusercontent.com/saifalbaghdadi/saifalbaghdadi/development/img/predict.png" width="600px" data-canonical- style="max-width: 250%">

## Author
### SAIF MALKSHAHI
