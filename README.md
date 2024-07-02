# Sentiment Analysis on Tweets
This project aims to perform sentiment analysis on tweets related to various vegetables. Using machine learning models, the sentiment of each tweet is classified as either positive or negative. The models used are: Logistic Regression, Decision Trees, KNN, Random Forest, XG Boost, SVM, and NLP (RoBERTa)

## Objective
The objective of this project is to accurately classify the sentiment of each tweet in the test dataset as either positive (1) or negative (0). This was made originally for a Kaggle Competition, where it ended up in 1st place with a 99% accuracy.

## Models Used
Several machine learning models are used to analyze the sentiment of the tweets:

1. <b>Logistic Regression</b>: A simple and efficient linear model for binary classification.
2. <b>Decision Trees</b>: A non-linear model that splits data into subsets based on feature values.
3. <b>K-Nearest Neighbors (KNN)</b>: A non-parametric model that classifies based on the majority vote of nearest neighbors.
4. <b>Random Forest</b>: An ensemble model that combines multiple decision trees to improve accuracy and control over-fitting.
5. <b>XGBoost</b>: An optimized gradient boosting model that enhances performance and speed.
6. <b>Support Vector Machine (SVM)</b>: A powerful model that finds the hyperplane which best separates the data into classes.
7. <b>Natural Language Processing (NLP) with RoBERTa</b>: A transformer-based model specifically designed for understanding the context of text. We have chosen RoBERTa over BERT as it is trained on more tweet-like data.

## Dataset
The dataset consists of tweets, labeled with a sentiment score:

### Training Dataset
- `Tweet_ID`: A unique integer identifying the tweet.
- `Sentiment`: The sentiment of the tweet (1 for positive, 0 for negative).
- `Tweet`: The content of the tweet.

The training dataset is expected to be a CSV file with the following structure:
```
Tweet_ID,Sentiment,Tweet
1,1,"I love carrots!"
2,0,"I hate broccoli."
...
```

### Test Dataset
- `Tweet_ID`: A unique integer identifying the tweet.
- `Tweet`: The content of the tweet.

The test dataset is expected to be a CSV file with the following structure:
```
Tweet_ID,Tweet
3,"Cauliflower is great!"
4,"I don't like spinach."
...
```

## Prerequisites
Ensure you have the following software installed:
- Python 3.x
- Jupyter Notebook
- Necessary Python libraries (imports are in the first cell)

## Model Evaluation
The models will be evaluated based on their accuracy in classifying the sentiment of tweets in the test dataset.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.
