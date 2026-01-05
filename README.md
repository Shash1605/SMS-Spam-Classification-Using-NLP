# SMS-Spam-Classification-Using-NLP
A comprehensive NLP pipeline for SMS Spam Detection. This project demonstrates end-to-end text processing—including Regex-based cleaning, stemming, and stop-word removal—followed by a comparative analysis of multiple Scikit-Learn classifiers and an Ensemble Voting model to achieve high-accuracy classification.

This project implements a machine learning solution to classify SMS messages as **Spam** or **Ham** (legitimate). It utilizes Natural Language Processing (NLP) techniques to transform raw text into numerical features and evaluates several classification algorithms to find the most effective model.

## 🚀 Features
- **Advanced Text Cleaning:** Uses Regular Expressions to identify and replace sensitive patterns like email addresses, URLs, phone numbers, and currency symbols.
- **NLP Pipeline:** Implements tokenization, stop-word removal, and Porter Stemming for text normalization.
- **Feature Engineering:** Constructs a Bag-of-Words model using the 1,500 most frequent terms.
- **Multiple Classifiers:** Compares SVC, K-Nearest Neighbors, Decision Trees, Random Forests, and Logistic Regression.
- **Ensemble Learning:** Uses a Hard Voting Classifier to combine the strengths of multiple models for more robust predictions.

## 🛠️ Tech Stack
- **Language:** Python
- **NLP Library:** NLTK
- **Machine Learning:** Scikit-Learn
- **Data Analysis:** Pandas, NumPy

## 📋 Project Workflow
1. **Data Preprocessing:** Convert labels to binary (0/1) and clean text using Regex.
2. **Feature Extraction:** Tokenize the processed text and filter using a frequency distribution.
3. **Data Splitting:** 75% Training and 25% Testing split.
4. **Model Training:** Wrap Scikit-Learn models using NLTK’s `SklearnClassifier`.
5. **Evaluation:** Performance measurement using Accuracy, Confusion Matrix, and Classification Reports (Precision/Recall).

## 📥 Installation & Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/spam-classification-nlp.git](https://github.com/your-username/spam-classification-nlp.git)
