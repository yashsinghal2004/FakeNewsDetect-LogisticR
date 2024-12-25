# Fake News Detection Model

## Introduction

This project is a Fake News Detection model built using Logistic Regression. The model leverages various Python libraries and a labeled dataset of news articles to distinguish between real and fake news.

---

## Libraries Used

The following Python libraries are used in this project and must be installed before running the code:

- **numpy**
- **pandas**
- **re**
- **nltk**
- **sklearn**

You can install these libraries using the following pip command:

```bash
pip install numpy pandas nltk scikit-learn
```

---

## Dataset

The dataset used for this project is `train.csv`, which contains labeled news articles. Download the dataset using the following link:

[Dataset Link](https://www.kaggle.com/c/fake-news/data)

After downloading, place the dataset in the root directory of the repository.

---

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone <https://github.com/yashsinghal2004/FakeNewsDetect-LogisticR.git>
   ```

2. Install the required libraries:

   ```bash
   pip install numpy pandas nltk scikit-learn
   ```

3. Download the dataset and place it in the repository directory.

4. Run the `main.ipynb` Jupyter Notebook to train and test the model:

   ```bash
   jupyter notebook main.ipynb
   ```

---

## Steps to Run the Model

The following steps outline the workflow of the project:

1. **Import Required Libraries:** Load all necessary Python libraries.

2. **Download Stopwords from nltk:**

   ```python
   import nltk
   nltk.download('stopwords')
   ```

3. **Load and Preprocess the Dataset:** Clean and prepare the data for analysis.

4. **Vectorize the Text Data:** Convert text data into numerical representations using appropriate techniques.

5. **Split the Data:** Divide the dataset into training and testing sets for model evaluation.

6. **Train the Model:** Train a Logistic Regression model on the training data.

7. **Evaluate the Model:** Assess the model’s accuracy on both the training and testing sets.

For detailed implementation steps, refer to the `main.ipynb` file in the repository.

---


