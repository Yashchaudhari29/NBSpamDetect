# NBSpamDetect
## Spam Classification with Naive Bayes

This project aims to classify text messages as spam or ham (non-spam) using Naive Bayes classifiers. It includes data preprocessing, exploratory data analysis, model training, evaluation, and comparison between Multinomial Naive Bayes (MNB) and Bernoulli Naive Bayes (BNB) models.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Overview
Spam classification is a common task in natural language processing (NLP) and machine learning. This project utilizes the Naive Bayes algorithm to classify text messages as either spam or ham based on their content.

## Dataset
The dataset used in this project is `spam.csv`, containing text messages labeled as spam or ham. It includes two columns: `Category` (spam or ham) and `Text` (the message content).

## Exploratory Data Analysis
Exploratory data analysis (EDA) involves analyzing the dataset to gain insights into its structure and characteristics. Key steps include:
- Checking for missing values
- Visualizing the distribution of message lengths
- Generating word clouds for spam and ham messages

## Data Preprocessing
Data preprocessing involves preparing the text data for modeling. Key steps include:
- Dropping unnecessary columns
- Renaming columns for clarity
- Adding a column for message lengths
- Vectorizing the text data using CountVectorizer

## Model Training
The project trains two Naive Bayes models:
- Multinomial Naive Bayes (MNB)
- Bernoulli Naive Bayes (BNB)

## Model Evaluation
Model evaluation includes:
- Calculating accuracy, precision, recall, and F1 score for each model
- Visualizing confusion matrices for model performance

## Results
The project compares the performance of MNB and BNB models in terms of various metrics such as accuracy, precision, recall, and F1 score.

## Usage
To use the trained models for classification:
1. Clone the repository.
2. Ensure all dependencies are installed.
3. Run the provided script with your text data.

## Dependencies
- [numpy](https://numpy.org/) (`pip install numpy`)
- [pandas](https://pandas.pydata.org/) (`pip install pandas`)
- [nltk](https://www.nltk.org/) (`pip install nltk`)
- [plotly](https://plotly.com/python/) (`pip install plotly`)
- [wordcloud](https://github.com/amueller/word_cloud) (`pip install wordcloud`)
- [matplotlib](https://matplotlib.org/) (`pip install matplotlib`)
- [scikit-learn](https://scikit-learn.org/stable/) (`pip install scikit-learn`)
- [seaborn](https://seaborn.pydata.org/) (`pip install seaborn`)

## Final Comparision between MNB and BNB

![image](https://github.com/Yashchaudhari29/NBSpamDetect/assets/119956179/fc2f36d3-493d-4bab-8fe5-56b2d56dc259)

