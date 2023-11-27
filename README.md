# MAIS202_Recipe-Recommendation
Final project for McGill AI Society Intro to ML Bootcamp (Fall 2023).

Training data retrieved from https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions

# Project description
The Recipe Recommendation App gives users recommendations based on recipes that they've previously liked. The model is built around a BERT model from Hugging Face which map sentences to vectors that were later used to calculate similarities between recipes. 

# Running the app
To run the web app, install all packages in requirements.txt. Then, change into the main directory of this repository and run

python app.py

Lastly, open a browser and navigate to your http://localhost:5000.

# Repository organization
static/
- CSS file for landing page

templates/
- HTML template for landing page

app.py
- main python script to instantiate Flask server
