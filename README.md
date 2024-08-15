# NLP Model for Identifying Salafi Jihadist Tweets in England

This repository contains the code and data for the final project titled **"Developing a Natural Language Processing Model to Identify Tweets Associated with the Salafi Jihadist Movement in England."** The project was conducted as part of the requirements for a B.Sc degree and is aimed at enhancing the ability to identify and monitor extremist content on social media platforms.

## Project Overview

The project leverages advanced machine learning techniques to develop a model that identifies linguistic and pragmatic features of tweets related to the Salafi Jihadist movement. The model was trained on a diverse and extensive dataset of carefully selected English-language tweets. The primary goal is to assist in the early detection of extremist content and contribute to security measures.

## Key Features

- **Multi-Model Approach**: Several models were developed and tested, including Support Vector Classifiers (SVC) with TF-IDF, deep learning models like MLP (Multi-Layer Perceptron) and LSTM (Long Short-Term Memory), with different sampling techniques like SMOTE (Synthetic Minority Over-sampling Technique) and Random Under Sampling.
- **Ensemble Model**: The final model is a combination of the best-performing individual models using a soft voting ensemble method. This approach provided the highest accuracy and reliability in identifying extremist tweets.
- **Data Visualization**: The project includes visualizations that help in understanding the distribution and characteristics of the data, such as word frequency distributions and class separation.

## Installation

To set up the project environment, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/username/repo_name.git
   cd repo_name
