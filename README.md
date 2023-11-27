# MAIS202_Recipe-Recommendation
Final project for McGill AI Society Intro to ML Bootcamp (Fall 2023).

Training data retrieved from https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions

# Project description
The Recipe Recommendation App gives users recommendations based on recipes that they've previously liked. The model is built around a BERT model from Hugging Face which maps sentences to vectors that were later used to calculate similarities between recipes. 

# Repository organization
static/
- CSS file for landing page

templates/
- HTML template for landing page

app.py
- main python script to instantiate Flask server
