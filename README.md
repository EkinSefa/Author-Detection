# 🖋️ Authorship Attribution with Machine Learning
This repository contains a comprehensive project aimed at identifying the authors of textual content using state-of-the-art text processing and machine learning techniques. The system addresses critical real-world challenges, including digital forgery detection, content management, and copyright infringement resolution.

## 🎯 Purpose
The primary goal of this project is to develop a robust authorship attribution system by combining advanced text preprocessing techniques, feature extraction methods, and machine learning algorithms.

## 📋 Scope
#### Datasets:

Diverse text types, including articles, blogs, and stories.

Rich linguistic and contextual variety for thorough model evaluation.

### Applications:

Detecting forged or plagiarized content.

Assisting in copyright and intellectual property management.

Enhancing automated content management systems.

## 🔧 Methods

📂 Data Preparation

### Text Cleaning:

Removed unnecessary elements such as punctuation, numbers, and special characters.

Normalized text by converting to lowercase and applying stemming or lemmatization.

### Language Detection:

Applied language-specific preprocessing techniques using libraries like LangDetect.

### Stop Word Removal:

Removed commonly used words that do not contribute significantly to meaning (e.g., "and," "the," "is").

## 🔍 Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency):
Captures statistical importance of words across documents.

Word2Vec:
Generates semantic word embeddings to capture contextual meaning and relationships between words.

## 🤖 Modeling

The following algorithms were implemented and evaluated:

### Machine Learning Models:

Random Forest

Logistic Regression

Support Vector Machines (SVM)

K-Nearest Neighbors (KNN)

Gradient Boosting

XGBoost

### Deep Learning Models:

Multi-Layer Perceptron (MLP)

Convolutional Neural Networks (CNN)

### Model Evaluation Metrics

Accuracy: Overall correctness of predictions
.
Precision: Proportion of correctly identified authors among all predictions for a specific author.

Recall: Proportion of correctly identified authors out of all actual instances for a specific author.

F1 Score: Harmonic mean of Precision and Recall.

## ✨ Results

## PAN18 Veri Seti Sonuçları


| Model                    | Accuracy | Precision | Recall | F1 Score |
|--------------------------|----------|-----------|--------|----------|
| Random Forest            | 47%      | 0.45      | 0.47   | 0.46     |
| Logistic Regression      | 41%      | 0.18      | 0.41   | 0.25     |
| SVM                      | 41%      | 0.17      | 0.41   | 0.24     |
| KNN                      | 38%      | 0.18      | 0.38   | 0.22     |
| Gradient Boosting        | 45%      | 0.41      | 0.45   | 0.43     |
| XGBoost                  | 46%      | 0.47      | 0.46   | 0.46     |
| Neural Networks (MLP)    | 42%      | 0.21      | 0.42   | 0.27     |



## PAN19 Dataset Results

| Model                       | Accuracy | Precision | Recall | F1 Score |
|-----------------------------|----------|-----------|--------|----------|
| Random Forest               | 75%      | 0.61      | 0.75   | 0.67     |
| Logistic Regression         | 78%      | 0.60      | 0.78   | 0.68     |
| SVM                         | 78%      | 0.60      | 0.78   | 0.68     |
| KNN                         | 73%      | 0.64      | 0.73   | 0.68     |
| Gradient Boosting           | 74%      | 0.62      | 0.74   | 0.67     |
| XGBoost                     | 76%      | 0.63      | 0.76   | 0.68     |
| Neural Networks (MLP)       | 78%      | 0.60      | 0.78   | 0.68     |

## 🛠️ Technologies

Programming Language: Python

Libraries and Tools:

Scikit-learn

NLTK (Natural Language Toolkit)

Gensim (Word2Vec)

Pandas

NumPy

TensorFlow/Keras

## 🌟 Applications

#### Digital Forgery Detection:

Identify instances of text forgery or plagiarism.

#### Content Management:

Automate attribution in large-scale content systems.

#### Copyright Infringement:

Assist in resolving intellectual property disputes.

## 🚀 How to Run

### Clone the repository:

```bash
[git clone https://github.com/EkinSefa/Author-Detection.git]
cd your-repo-name
```
### Install dependencies:

```bash
Kodu kopyala
pip install -r requirements.txt
```
### Run the script:

```bash
python main.py
```
Analyze the results in the generated output files.