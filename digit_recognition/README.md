# Handwritten Digit Recognition with Naive Bayes Classifier
This repository contains Python code for performing handwritten digit recognition using the Naive Bayes classifier. The dataset used for this task is the famous MNIST dataset.

## Introduction
Handwritten digit recognition is a fundamental problem in the field of machine learning and computer vision. It involves identifying the digits (0-9) present in handwritten images. In this project, we use the MNIST dataset, which consists of 28x28 pixel images of handwritten digits.

## Requirements
To run the code in this repository, ensure you have the following dependencies installed:

```
Python (>=3.6)
scikit-learn
matplotlib
seaborn
```

You can install these dependencies using pip:
`pip install scikit-learn matplotlib seaborn`

## Usage
1. Clone this repository to your local machine:
    `git clone https://github.com/your-username/digit-recognition-naive-bayes.git`

2. Navigate to the cloned repository:
    `cd digit-recognition-naive-bayes`

3. Run the Python script:
    `python digit_recognition.ipynb`

## Explanation
* The digit_recognition.py script loads the MNIST dataset using scikit-learn's load_digits function.
* It visualizes a sample of the dataset by displaying images of handwritten digits.
* Dimensionality reduction is performed using Isomap to visualize the data in 2D.
* The data is split into training and testing sets.
* The Naive Bayes classifier is trained on the training data.
* The trained model is evaluated on the testing data, and accuracy and confusion matrix are computed.

## Results
The script generates visualizations of the dataset, including scatter plots of the projected data points, as well as a confusion matrix to evaluate the performance of the Naive Bayes classifier.