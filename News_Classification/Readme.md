# BBC-News-Classification

A machine learning project that classifies BBC news articles into categories such as Business, Tech, Entertainment, Sport, and Politics. The dataset is sourced from Kaggle’s “Learn AI BBC” (https://www.kaggle.com/competitions/learn-ai-bbc) competition.

## Table of Contents
- [Overview](#overview)
- [Project Goals](#project-goals)
- [Dataset](#dataset)
- [Methods](#methods)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

---

## Overview
This repository demonstrates several NLP techniques on a BBC News dataset. It starts with data cleaning and unsupervised topic modeling (NMF) before moving to supervised classification with classical machine learning and modern Transformer-based models (BERT/Roberta).
## Project Goals

Project Goals

1. Explore multiple NLP methods—both unsupervised (NMF) and supervised (Logistic Regression, Naïve Bayes, BERT).
2. Compare performance of different models on BBC articles.
3. Generate Kaggle-ready submission files and achieve a high classification accuracy.

## Dataset
- **Source:**  Kaggle’s “Learn AI BBC” (https://www.kaggle.com/competitions/learn-ai-bbc)
- **Details:** 
  - Contains text articles from BBC covering topics such as Business, Tech, Entertainment, Sport, and Politics.

## Methods
1. **Data Cleaning:** Removing punctuation, lowercasing, optional stopword removal, etc.
2. **Exploratory Data Analysis (EDA):** Investigated patterns and relationships in the data.
3. **Unsupervised Approach:** Non-negative Matrix Factorization (NMF) for topic modeling/clustering.
4. **Supervised Classical Models:** Evaluated two machine learning models:
   - Logistic Regression
   - Multinomial Naïve Bayes
5. **Transformer-Based Models:** BERT/Roberta fine-tuning for classification.

## Results
NMF (Unsupervised): Gained insight into latent topics; used label permutation for alignment (95.102%).
Multinomial NB: Achieved strong accuracy (97.414%).
BERT/Roberta: Reached the highest test accuracy on Kaggle (98.775%).

## Installation
1. Clone the repository:
   ```bash
   git clone <link>

2. Navigate to the project directory:
   ```bash
   cd BBC-News-Classification

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook BBC-News-Classification.ipynb
   
2. Place BBC News train/test CSV files into data/ or specify the path in your notebook.
3. Follow the steps in the notebook to reproduce the analysis.

## Acknowledgments

- **Dataset:** This project utilizes the ([Learn AI BBC Data](https://www.kaggle.com/competitions/learn-ai-bbc/data)).

