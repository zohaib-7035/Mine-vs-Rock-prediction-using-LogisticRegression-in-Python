**Rock vs Mine Prediction**

**Overview:**

This project is a machine learning model that predicts whether an object is a rock or a mine based on sonar data. The dataset used contains numerical frequency-based attributes derived from sonar signals, with labels indicating whether the object is a rock (R) or a mine (M).

**Dataset:**

The dataset consists of 60 numerical features extracted from sonar signals, followed by a target label (column 60) which indicates:

R (Rock)

M (Mine)

**Technologies Used:**

Python

NumPy

Pandas

Scikit-learn (for machine learning and evaluation)

**Project Workflow:**

Data Loading: Read the sonar dataset using Pandas.

Exploratory Data Analysis

Display basic statistics.

Count class distribution.

Compute the mean for each class.

**Data Preprocessing**:

Separate features and labels.

Split data into training and testing sets (90% training, 10% testing).

Model Selection: Logistic Regression is used for classification.

Model Training: Train the model using the training data.

**Model Evaluation:**

Measure accuracy on training and testing datasets.

**Results**

The accuracy of the model is measured on both training and testing datasets to evaluate its performance.
