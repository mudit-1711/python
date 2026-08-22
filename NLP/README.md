# Natural Language Processing (NLP)

This directory hosts machine learning and natural language processing projects designed to analyze and predict emotions from text.

## Directory Structure

*   **[`ML_NLP.ipynb`](file:///d:/python/NLP/ML_NLP.ipynb)**: A Jupyter notebook dedicated to exploring NLP fundamentals, text preprocessing, feature extraction, and training baseline text classification models.
*   **[`emotions.txt`](file:///d:/python/NLP/emotions.txt)**: A text dataset mapping phrases/sentences to distinct human emotions.
*   **[`emotionspredictor/`](file:///d:/python/NLP/emotionspredictor/)**: An interactive Streamlit web application ("Emotify") that runs a live emotion prediction model.

## Key Workflows & Techniques

### 1. Text Preprocessing
*   Converting text to lowercase.
*   Removing punctuation and special characters using Python's `string` library.
*   Tokenization (splitting text into individual words).
*   Removing common English stopwords using `nltk` (Natural Language Toolkit).

### 2. Feature Extraction & Vectorization
Converting raw text documents into numerical feature vectors using:
*   **Bag of Words (`CountVectorizer`)**: Counting occurrences of words.
*   **TF-IDF (`TfidfVectorizer`)**: Calculating Term Frequency-Inverse Document Frequency to weigh words according to their significance.

### 3. Classification Models
*   **Naive Bayes (`MultinomialNB`)**: Baseline probabilistic classification model suited for text features.
*   **Logistic Regression (`LogisticRegression`)**: Standard classification model mapping text features to classification labels.

---

## 🚀 Projects

### Emotify - Emotion Predictor App
Located in the **[`emotionspredictor/`](file:///d:/python/NLP/emotionspredictor/)** subfolder, **Emotify** is a complete, interactive Streamlit web application. It uses a trained model to predict the probability of six core emotions from user text inputs:
*   😊 Joy
*   😢 Sadness
*   😠 Anger
*   😨 Fear
*   ❤️ Love
*   😲 Surprise

For setup and deployment instructions for the web application, please see the dedicated **[`emotionspredictor/README.md`](file:///d:/python/NLP/emotionspredictor/README.md)**.
