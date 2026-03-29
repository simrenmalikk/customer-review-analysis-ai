# Customer Review Analysis using Machine Learning

## Overview
This project analyzes customer reviews using machine learning techniques to classify sentiment as positive or negative. The goal is to demonstrate how AI can be used to extract meaningful insights from textual data.

## Research Question
How can machine learning be used to analyze customer reviews and support decision-making?

## Dataset
The dataset used is the Amazon Polarity dataset, accessed via the Hugging Face datasets library. A subset of approximately 2000 reviews was selected for this project. Each review is labeled as either positive (1) or negative (0).

## Methodology

### Data Preparation
The dataset was loaded and converted into a pandas DataFrame containing review text and corresponding sentiment labels.

### Feature Extraction
Text data was transformed into numerical features using TF-IDF vectorization.

### Model Training
A Logistic Regression model was trained on the dataset using an 80/20 train-test split.

### Evaluation
Model performance was evaluated using accuracy on the test set.

## Results
The model achieved an accuracy of approximately 0.77. It correctly classified most reviews, although some misclassifications occurred in more ambiguous cases.

## Interpretation
The results show that even simple machine learning models can effectively identify sentiment patterns in text data. This approach can be useful for analyzing customer feedback and identifying trends.

## Limitations
- Small dataset subset used
- No advanced preprocessing techniques applied
- No deep learning models used
- Evaluation limited to accuracy metric

## Future Work
- Apply transformer-based models such as BERT
- Use larger datasets for improved performance
- Incorporate additional evaluation metrics
- Perform topic modeling to extract key themes

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Hugging Face Datasets
- Google Colab
