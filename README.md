# Deep Learning Projects

## Overview

This repository contains a collection of practical deep learning projects designed to develop and apply fundamental concepts in **Deep Learning, Tensor Operations, Neural Networks, Image Classification, and Binary Classification**.

The project is divided into two main parts:

- **Part 1 — Deep Learning Fundamentals & Image Classification**
- **Part 2 — Pima Indians Diabetes Prediction**

The first part focuses on understanding tensors and applying neural networks to image classification tasks. The second part applies deep learning techniques to a real-world binary classification problem.

---

# Part 1 — Deep Learning Fundamentals & Image Classification

## 1. Tensor Operations

The first notebook focuses on understanding and testing fundamental **tensor operations**, which are essential building blocks of modern deep learning frameworks.

### Topics Covered

- Creating tensors
- Tensor shapes and dimensions
- Indexing and slicing
- Reshaping tensors
- Tensor arithmetic
- Matrix operations
- Broadcasting
- Tensor manipulation
- Basic mathematical operations

This section provides the foundation for understanding how data is represented and manipulated inside neural networks.

---

## 2. Handwritten Digit Classification — MNIST

The second project focuses on classifying handwritten digits using the **MNIST dataset**.

### Objective

The goal is to develop a neural network capable of recognizing handwritten digits from **0 to 9**.

### Workflow

- Load the MNIST dataset
- Explore the image data
- Preprocess the images
- Normalize pixel values
- Split the data into training and testing sets
- Build a neural network
- Train the model
- Validate the model
- Evaluate the model on unseen data
- Analyze the classification results

### Classification Task

The model performs **10-class classification**:

```text
0  1  2  3  4  5  6  7  8  9

#Part 2 - Pima Indians Diabetes Prediction — Deep Learning

## Overview

This project focuses on applying **Deep Learning and Neural Networks** to a binary classification problem using the **Pima Indians Diabetes Dataset**.

The objective is to develop a neural network capable of predicting whether a person is likely to have diabetes based on several medical and demographic features.

The project covers the complete deep learning workflow, from **data exploration and preprocessing to neural network training, validation, and evaluation**.

---

# 1. Dataset

The project uses the **Pima Indians Diabetes Dataset**, which contains medical diagnostic measurements that can be used to predict the presence of diabetes.

### Features

| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age of the individual |
| Outcome | Target variable |

### Target

The `Outcome` column represents the target variable:

```text
0 → Non-diabetic
1 → Diabetic

#2.Project Workflow

Pima Diabetes Dataset
        ↓
Exploratory Data Analysis
        ↓
Missing / Invalid Value Analysis
        ↓
Outlier Analysis
        ↓
Data Preprocessing
        ↓
Feature Scaling
        ↓
Train-Test Split
        ↓
Neural Network Construction
        ↓
Model Compilation
        ↓
Model Training
        ↓
Validation
        ↓
Learning Curves
        ↓
Test Evaluation
        ↓
Confusion Matrix
        ↓
Classification Metrics
        ↓
Final Analysis


## 3. Short Reflection

### Why did you choose this dataset?

I chose the Pima Indians Diabetes Dataset because it provides a practical **binary classification problem** that can be solved using a neural network. It allowed me to apply deep learning concepts to structured medical data rather than image data, making the project different from the MNIST and Fashion-MNIST classification tasks.

### What challenges did you face?

One of the main challenges was dealing with **data quality issues**, particularly zero values in features such as Glucose, BloodPressure, SkinThickness, Insulin, and BMI. I also had to analyze the presence of outliers and determine how they could affect neural network training.

Another challenge was finding a suitable neural network configuration and monitoring the training and validation curves to avoid overfitting.

### What improvements did you try?

I experimented with different aspects of the neural network, including the **model architecture, optimizer, and training process**. I also focused on proper feature scaling and monitored both training and validation performance to improve the model's generalization.

Different evaluation metrics such as **precision, recall, and F1-score** were also considered instead of relying only on accuracy.

### What did you learn?

This project helped me understand how to apply a complete **deep learning workflow to tabular data**. I learned the importance of preprocessing, feature scaling, outlier analysis, neural network architecture, model optimization, and validation.

I also learned that for medical classification problems, **accuracy alone is not always sufficient**. Metrics such as recall can be particularly important because false negative predictions may have significant consequences.
