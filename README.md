
# Predictive Analytics Lab Exam – 2

## Objective

The aim is to develop a machine learning classification model that can accurately predict the target variable based on the provided dataset.

## Dataset

The dataset consists of two input features and one output (target) variable.

**Input Features**

* Feature1
* Feature2

**Target Variable**

* Yes
* No

## Exploratory Data Analysis (EDA)

Initial data exploration was conducted to gain insights into the dataset. The following steps were performed:

* Examined the dataset’s shape and structure
* Identified any missing or null values
    - There were missing values in  the dataset and  they were cleaned
* Analyzed the distribution of the target classes using a count plot
     <img width="569" height="425" alt="image" src="https://github.com/user-attachments/assets/6ab2dc22-020b-414a-a315-6face58685a8" />

* Explored the relationship between Feature1 and Feature2 through a scatter plot
      <img width="550" height="418" alt="image" src="https://github.com/user-attachments/assets/bf4dc9d8-b27b-4dd2-9985-77b0dbee5dda" />


## Data Preprocessing

To prepare the data for model training, the following preprocessing steps were applied:

* Encoded the target variable by converting categorical labels (Yes/No) into numerical format (1/0)
* Evaluated the dataset for class imbalance
     <img width="555" height="432" alt="image" src="https://github.com/user-attachments/assets/239c4abe-293f-4b01-b686-f679a524c405" />

* Divided the dataset into training and testing subsets

## Model Development

A Logistic Regression model was implemented to learn patterns from the data and perform binary classification.

## Decision Boundary Visualization

A decision boundary plot was created to illustrate how the model differentiates between the two classes based on Feature1 and Feature2.
  <img width="569" height="428" alt="image" src="https://github.com/user-attachments/assets/7dba9608-d981-4d9d-9d00-8976ff934bb9" />


## Model Evaluation

The model’s performance was assessed using the following metrics:

* Accuracy Score 
* Confusion Matrix
* Classification Report, including Precision, Recall, and F1-score
   <img width="420" height="173" alt="image" src="https://github.com/user-attachments/assets/764aeaf3-205e-4f0e-829f-acf6bff64374" />


## Tools and Libraries

The implementation was carried out using the following tools and libraries:

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
