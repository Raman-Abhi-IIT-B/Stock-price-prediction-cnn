# Stock-price-prediction-cnn

This repository contains all the code for the project 'Stock Price Prediction using CNN'. The input features include 80 variables which have been grouped into: 
</br>**1. Technical Indicators** </br>
**2. Price of Commodities** </br>
**3. Price of Currencies** w.r.t the dollar </br>
**4. Future Markets** etc. </br> </br>

The output is binary: 1 if the price fluctiuation for the next day is positive and 0 if it is negative. </br> </br>

A CNN network based on AlexNet architecture was built, and I applied ReLU and sigmoid activation functions to boost the model, MAE to evaluate loss & Adam optimizer to train the Neural Network. A final **F1 score** of **0.699** was obtained.
