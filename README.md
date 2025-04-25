# MADE(MAIL DETECTION)-PROJECT

## Spam SMS Detection (Spam or Ham Classification)

## Project Overview
This project aims to develop an SMS classification model that identifies spam and non-spam messages (ham). Using machine learning techniques, the model can effectively distinguish between spam and legitimate SMS messages.

## Table of Contents

Objective

Dataset

Technologies Used

Data Preprocessing

Modeling

Performance

Installation

Usage

License

## Objective
The goal of this project is to build a robust SMS classification model capable of classifying messages as either spam or ham. The model is trained on a labeled dataset approximately 11,000 SMS messages.

## Dataset

Dataset Size: 11,000 SMS messages.

Labels: Each message is labeled as either "spam" or "ham".

Source: The dataset was pre-labeled and used for training the model.

## Technologies Used

Python: Programming language.

Jupyter Notebook: Environment for developing and testing the model.

## Libraries:

pandas for data manipulation.

numpy for numerical operations.

scikit-learn for machine learning models.

matplotlib & seaborn for data visualization.

nltk for text processing and tokenization.

## Data Preprocessing

Text Cleaning: Removed special characters, numbers, and unnecessary whitespaces.

Text Vectorization: Used TF-IDF (Term Frequency-Inverse Document Frequency) for text vectorization.

Train-Test Split: The dataset was split into training and testing sets to evaluate model performance.

## Modeling
## Modeling Techniques:

Used several machine learning algorithms to find the best model for SMS classification.

Experimented with models such as Naive Bayes and Logistic Regression.

Hyperparameter Tuning: Implemented grid search to fine-tune model parameters for optimal performance.

## Performance
Accuracy: Achieved 98% accuracy on the test set.

The model demonstrated high precision in distinguishing spam from ham messages, providing a robust solution for SMS classification.

## Installation
To run this project locally, follow these steps:

## Clone the repository:

git clone https://github.com/lav2024/spam-sms-detection.git

## Install required dependencies:


pip install -r requirements.txt

## Usage
Once you’ve installed the dependencies, you can run the notebook in Jupyter to explore the project and test the model.

## Launch Jupyter Notebook:

jupyter notebook
Open Spam_SMS_Detection.ipynb and run the cells.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

