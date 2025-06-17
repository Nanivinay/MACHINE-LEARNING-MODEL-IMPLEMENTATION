# MACHINE-LEARNING-MODEL-IMPLEMENTATION

COMPANY : CODTECH IT SOLUTIONS
NAME : SUNKARI VINAY KUMAR
INTERN ID : CT04DN68
DOMAIN : PYTHON PROGRAMMING
MENTOR : NEELA SANTOSH

#  SMS Spam Detection using Machine Learning (Naive Bayes)

A simple machine learning model implemented in Python using **Scikit-Learn** and **Naive Bayes** classifier to classify SMS messages as **Spam** or **Ham (Not Spam)**.


# Project Overview

This project builds a **predictive classification model** that analyzes text messages and predicts whether they are spam or not. It uses a **Naive Bayes algorithm** and **CountVectorizer** to transform text data into numerical vectors for model training and testing.


# Dataset

-  **Source:** [SMS Spam Collection Dataset](https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv)
- **Format:** Tab Separated Values (.tsv)
- **Columns:**
  - `label` : Message category (`ham` or `spam`)
  - `message` : The actual SMS content

# Technologies & Libraries Used

- Python 
- Pandas 
- Numpy 
- Scikit-learn 
- CountVectorizer
- Multinomial Naive Bayes Classifier
- Jupyter Notebook (for implementation)

# Workflow

1. **Data Loading**
   - Load dataset from an online source.
  
2. **Data Preprocessing**
   - Check for missing values.
   - Convert labels (`ham`, `spam`) to numerical values (`0`, `1`).

3. **Data Splitting**
   - Split data into 80% training and 20% testing sets.

4. **Text Vectorization**
   - Use `CountVectorizer` to convert text messages into numerical vectors.

5. **Model Training**
   - Train a Multinomial Naive Bayes classifier on the training data.

6. **Model Prediction**
   - Predict labels for the test data.

7. **Model Evaluation**
   - Evaluate accuracy, confusion matrix, and classification report.

8. **Custom Prediction**
   - Test the model with your own custom message input.


# Model Performance

- **Accuracy:** ~98.4%
- **Confusion Matrix:**  
  |      | Predicted Ham | Predicted Spam |
  |:-----|:--------------|:--------------|
  | Actual Ham  | 966            | 2              |
  | Actual Spam | 15             | 132            |

- **Classification Report:**  
  - High precision, recall, and f1-score for both categories.

---

## 📋 Sample Custom Prediction

**Message:**  
`"Congratulations! You have won a free ticket to Bahamas. Call now!"`

**Prediction Output:**  
`Spam`


# How to Run the Project

1. Install required libraries (if not installed):
   pip install pandas numpy scikit-learn
Open the Jupyter Notebook or Python script file.

Run all the cells / code sections sequentially.

Deliverable :
A Jupyter Notebook or Python script showcasing:

- Dataset loading

- Preprocessing

- Model implementation

- Evaluation metrics

- Sample custom prediction

RESULT :

![Image](https://github.com/user-attachments/assets/5256cc28-baf3-4ab4-b3b1-0474c66d721d)
![Image](https://github.com/user-attachments/assets/6f3faa5b-bb71-4842-9085-8dc3533e2f96)
