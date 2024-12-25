Fake News Detection Model

Introduction

This project is a Fake News Detection model built using Logistic Regression. The model leverages various Python libraries and a labeled dataset of news articles to distinguish between real and fake news.

Libraries Used

The following Python libraries are used in this project and must be installed before running the code:

numpy

pandas

re

nltk

sklearn

You can install these libraries using the following pip command:

pip install numpy pandas nltk scikit-learn

Dataset

The dataset used for this project is train.csv, which contains labeled news articles. Download the dataset using the following link:

Dataset Link (Replace # with the actual dataset link)

After downloading, place the dataset in the root directory of the repository.

Usage

Clone the repository to your local machine:

git clone <repository_url>
cd <repository_directory>

Install the required libraries:

pip install numpy pandas nltk scikit-learn

Download the dataset and place it in the repository directory.

Run the main.ipynb Jupyter Notebook to train and test the model:

jupyter notebook main.ipynb

Steps to Run the Model

The following steps outline the workflow of the project:

Import Required Libraries: Load all necessary Python libraries.

Download Stopwords from nltk:

import nltk
nltk.download('stopwords')

Load and Preprocess the Dataset: Clean and prepare the data for analysis.

Vectorize the Text Data: Convert text data into numerical representations using appropriate techniques.

Split the Data: Divide the dataset into training and testing sets for model evaluation.

Train the Model: Train a Logistic Regression model on the training data.

Evaluate the Model: Assess the model’s accuracy on both the training and testing sets.

For detailed implementation steps, refer to the main.ipynb file in the repository.
