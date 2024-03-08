# classification-challenge
UNC Chapel Hill AI Bootcamp Module 13 Challenge

# Background
Let's say you work at an Internet Service Provider (ISP) and you've been tasked with improving the email filtering system for its customers. You've been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. The ISP wants you to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

You will be creating two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models you'll create will be a logistic regression model and a random forest model.

# Files
One jupyter notebook "spam_detector.ipynb" holds the entire application/modeling and analysis. This file shows that Random Forest Classifier is the best The starter code was provided with this challenge to get us started. 

# Functions/Dependencies
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomForestClassifier

# Analysis
Findings show that the Random Forest Model performs the best for dectecting spam as it is aligned to best predict discrete targets like spam filtering. 