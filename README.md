# Customer Review Analysis using ML

## Overview
This project analyzes customer reviews using machine learning techniques to classify sentiment (positive or negative) and extract useful insights for decision-making.

## Research Question
How can AI be used to analyze customer reviews and extract useful insights for business decisions?

## Dataset
- Source: Amazon Polarity Dataset (via Hugging Face)
- Subset used: ~2000 reviews
- Each review is labeled as:
  - 0 → Negative
  - 1 → Positive

## Methodology

### 1. Data Loading
- Loaded dataset using Hugging Face `datasets`
- Selected a subset for faster experimentation

### 2. Preprocessing
- Extracted review text and labels
- Converted data into a structured pandas DataFrame

### 3. Feature Extraction
- Used **TF-IDF (Term Frequency–Inverse Document Frequency)** to convert text into numerical features

### 4. Model Training
- Model: Logistic Regression
- Split data into:
  - 80% Training
  - 20% Testing

### 5. Evaluation
- Metric used: Accuracy score
- 
## Results
- Model Accuracy: **~0.77**
- The model correctly classifies most customer reviews
- Some misclassifications remain, especially in ambiguous reviews

## Interpretation
- Machine learning can effectively analyze customer sentiment
- Even simple models can capture patterns in text data
- Useful for:
  - Understanding customer satisfaction
  - Identifying product issues
  - Supporting business decisions

##Limitations
- Small subset of dataset used
- No deep learning models applied
- No advanced text preprocessing (e.g., stemming, stopword removal)
- Limited evaluation metrics (only accuracy)

## Future Work
- Use transformer models (e.g., BERT) for improved performance
- Apply topic modeling to extract key themes
- Use larger datasets for better generalization
- Improve preprocessing techniques

##Technologies Used
- Python
- Pandas
- Scikit-learn
- Hugging Face Datasets
- Google Colab
