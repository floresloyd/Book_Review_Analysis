# Book Review Classifier

## Overview
The Book Review Classifier is a machine learning project aimed at categorizing book reviews into positive or negative sentiments based on the text of the review. This classifier can be instrumental in understanding customer opinions and aiding in the recommendation systems.

## Data
The dataset, `bookreview.csv`, comprises two columns:
- `review`: Contains the text of the book review.
- `label`: Indicates whether the review is positive (`1`) or negative (`0`).

## Objective
The primary objective is to develop a model that can accurately classify an incoming review as positive or negative, utilizing the textual content provided.

## Folder Structure
### 1. Data Cleaning
This folder contains scripts and notebooks for:
- Converting the review text into word embeddings.
- Creating feature vectors from these word embeddings, which serve as input to the machine learning models.

### 2. Models Explored
In this folder, you will find different machine learning models used for classification:
- **Logistic Regression**: A simple yet effective model for binary classification.
- **Random Forest**: A robust model suitable for handling complex data structures.
- **Neural Networks**: Advanced models that can capture intricate patterns in text data.

## Getting Started
To use this project, follow these steps:
1. Clone the repository.
2. Install the required dependencies.
3. Navigate to the `Data Cleaning` folder to start preprocessing the dataset.
4. Experiment with different models in the `Models Explored` folder to train and evaluate the classifiers.

## Contributing
Contributions are welcome! You can contribute by:
- Enhancing the existing models.
- Proposing new feature engineering techniques.
- Improving the data preprocessing steps.



