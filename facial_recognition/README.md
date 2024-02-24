# Facial Recognition with Support Vector Machines (SVM)
This repository contains Python code for performing facial recognition using Support Vector Machines (SVM) with Principal Component Analysis (PCA) for dimensionality reduction.

## Introduction
Facial recognition is a popular application of machine learning, with numerous practical applications such as biometric security systems, identity verification, and image classification. In this project, we use the Labeled Faces in the Wild (LFW) dataset, which contains images of people's faces collected from the internet. We employ SVM, a supervised learning algorithm, to classify faces into different categories.

## Requirements
To run the code in this repository, you need the following dependencies:

```
Python (>=3.6)
scikit-learn
matplotlib
seaborn
```

You can install them using pip and the provided requirements.txt file:
`pip install -r requirements.txt`

## Usage
1. Clone this repository to your local machine:
    `git clone https://github.com/your-username/facial-recognition-svm.git`

2. Navigate to the cloned repository:
    `cd facial-recognition-svm`

3. Run the Python script:
    `python facial_recognition.ipynb`


## Explanation
* The facial_recognition.py script loads the LFW dataset using scikit-learn's fetch_lfw_people function.
* It preprocesses the data and performs dimensionality reduction using PCA to reduce the number of features.
* SVM is used for classification, with hyperparameters tuned using Grid Search.
* The script then evaluates the model's performance using various metrics and visualizations.

## Results
The script generates visualizations of the predicted faces, classification reports, and confusion matrices to evaluate the model's performance.