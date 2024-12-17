Technical Description:
Text Preprocessing:

Uses regular expressions to clean the text (removes special characters and numbers).
NLTK is used for stopword removal and sentence tokenization.
Feature Extraction:

Grammar errors are detected using spaCy for out-of-vocabulary (OOV) word identification.
Sentence structure is analyzed with NLTK to calculate average sentence length.
Content features are extracted using TF-IDF vectorization.
Machine Learning:

A Linear Regression model is trained on extracted features to predict essay scores.
Feedback Generation:

Provides feedback on grammar, sentence structure, and content quality based on extracted features.
Model and Vectorizer Storage:

The trained model and TF-IDF vectorizer are saved using pickle for future predictions.
Libraries Used:

pandas for data handling.
spaCy for grammar analysis.
scikit-learn for machine learning and vectorization.
NLTK for text preprocessing and feature extraction.
