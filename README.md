# Graduate Admission Prediction

This repository contains code for predicting graduate admission chances based on various parameters using a neural network model.

## Introduction

In the competitive landscape of higher education, predicting graduate admission chances accurately can be crucial for both prospective students and educational institutions. This project aims to provide a predictive model that can estimate the likelihood of admission based on factors such as GRE scores, TOEFL scores, university rating, etc.

## Dataset

The dataset used for this project is the "Graduate Admissions" dataset available on Kaggle, provided by Mohan S Acharya. It consists of various parameters such as GRE scores, TOEFL scores, university rating, Statement of Purpose (SOP) score, Letter of Recommendation (LOR) score, undergraduate GPA, and research experience.

You can find the dataset [here](https://www.kaggle.com/mohansacharya/graduate-admissions).

## Model Architecture

The model architecture used for this prediction task is a feedforward neural network implemented using TensorFlow and Keras. The neural network consists of three dense layers:

1. **Input Layer**: The input layer with 7 units corresponding to the 7 features in the dataset.
2. **Hidden Layers**: Two hidden layers with 7 units each, utilizing ReLU activation functions to introduce non-linearity.
3. **Output Layer**: The output layer with 1 unit, employing a linear activation function for regression.

The model is trained using the mean squared error loss function and the Adam optimizer.



