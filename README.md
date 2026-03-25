# Malaysian NLP Sentiment Analysis

This project focuses on building a Natural Language Processing (NLP) system for sentiment analysis on Malaysian text datasets. It demonstrates the full machine learning pipeline including preprocessing, feature engineering, model training, evaluation, and tuning.

## Overview

The project processes raw text data and transforms it into structured features for classification. It includes multiple datasets, preprocessing steps, and evaluation results to analyze model performance.

## Key Features

- Text preprocessing (cleaning, tokenization, stopword removal)
- Handling out-of-vocabulary (OOV) words
- Feature engineering and transformation
- Model training and evaluation
- Performance analysis (accuracy, F1-score, kappa score)
- Hyperparameter tuning

## Project Structure

```text
├── Preprocessing.ipynb        # Data cleaning and preprocessing
├── Modeling.ipynb            # Model training and evaluation
├── DeploymentGUI.ipynb       # Interface for model usage

├── saved_model/              # Trained model (ignored in Git)

├── Data Files
│   ├── HLPTrain.csv
│   ├── HLPTest.csv
│   ├── HLPValid.csv
│   ├── RojakSentimentTrain.csv
│   ├── RojakSentimentTest.csv
│   ├── RojakSentimentValid.csv

├── Processed Data
│   ├── train_preprocessed.csv
│   ├── test_preprocessed.csv
│   ├── valid_preprocessed.csv

├── Results
│   ├── hlp_kappa_scores.txt
│   ├── tuningResults.csv
│   ├── classification reports

├── Utilities
│   ├── cn_stopwords.txt
│   ├── malaysian.txt
│   ├── NLP_OOV.txt
```
## Methodology
1. Data preprocessing:
- Remove noise and irrelevant characters
- Normalize text
- Remove stopwords
- Handle OOV words

2. Feature Engineering:
- Convert text into numerical representation

3. Model Training:
- Train classification models on processed data

4. Evaluation:
- Accuracy
- F1-score
- Kappa score

5. Hyperparameter Tuning:
Improve model performance

## Technologies Used
Python
Pandas
Scikit-learn
Jupyter Notebook
NLP techniques

## Results

The model performance was evaluated using multiple metrics, including classification reports and kappa scores. The results demonstrate effective sentiment classification on Malaysian text datasets.

## How to Run
1. Open the project in Jupyter Notebook
2. Run:
- Preprocessing.ipynb
- Modeling.ipynb
- DeploymentGUI.ipynb
