# Fake-News-Prediction

A project to detect fake news using Machine Learning and Python. 

Find the dataset here: https://www.kaggle.com/competitions/fake-news/data

## Detection model building process
1. Data Collection
2. Data Preprocessing (in this project, the text data of the news articles haven't been considered since it needs a lot of computational power to execute. Therefore as the training and testing data, the combination of title and author was used as a new variable called 'content')
3. Split the dataset to train and test data
4. Training **Logistic Regression Model** (Since there is a binary classification of real and fake news)
5. Evaluate the trained model with testing data
6. Prediction system

