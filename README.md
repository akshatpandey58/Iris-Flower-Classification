
# Iris Flower Classification Using Machine Learning

"Cultivating insights from nature, the Iris Flower Classification project harnesses the elegance of machine learning to distinguish between iris flower species with remarkable precision. Delve into our repository to uncover the intricacies of our approach, from data preprocessing to model selection and evaluation. Whether you're a budding data scientist or a seasoned enthusiast, join us on this journey of exploration and discovery."



## Importing Libraries
import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sb

from sklearn.model_selection import train_test_split

from sklearn.neighbors import KNeighborsClassifier

from sklearn import metrics

from sklearn.metrics import classification_report,confusion_matrix

from sklearn.metrics import accuracy_score

from sklearn.datasets import load_iris

## Loading datasets
iris=load_iris()

## Finding useful info about the dataset

## After Cleaning Dataset


## Machine Learning Algorithms

Split the Dataset into Training and Testing Dataset

Employeed K-Nearest Neighbour Algorithms to make classification

Calculated precision score,recall value and f1 score to feature the accuracy
