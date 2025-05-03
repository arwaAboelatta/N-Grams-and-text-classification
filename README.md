## 📚 Overview

The project is divided into two main parts:

### 🔹 Part 1: N-gram Language Modeling (IMDB Dataset)

We built a statistical N-gram language model using the unsupervised IMDB movie reviews dataset. Key steps included:

- Text preprocessing: tokenization, lowercasing, punctuation removal
- Building unigram, bigram, and trigram models
- Implementing Laplace smoothing for better generalization
- Evaluating model performance using **perplexity**

### 🔹 Part 2: Sentiment Classification (SST Dataset)

We performed sentiment classification using the **Stanford Sentiment Treebank (SST)** dataset 
with the goal of classifying sentences into sentiment classes:


This part includes:

#### 2.1 Naive Bayes Classifier
- Implemented from scratch using NumPy
- Compared against `MultinomialNB` from Scikit-learn

#### 2.2 Logistic Regression
- Implemented from scratch using NumPy and bigram features
- Compared against `LogisticRegression` and `SGDClassifier` from Scikit-learn

#### 2.3 Evaluation
- Computed **confusion matrix**, **precision**, **recall**, and **F1 score**
- Implemented evaluation metrics from scratch and verified against Scikit-learn metrics

## 📊 Tools & Libraries

- Python, NumPy
- Scikit-learn (for comparison)
- Jupyter Notebook

## 🧠 Learning Outcomes

- Understanding of N-gram modeling and smoothing techniques
- Hands-on experience with text classification and evaluation
- Implementation of fundamental ML algorithms from scratch



