# Optimal-Drug-for-Patients-Using-Decision-Trees
This project utilizes Decision Tree classification algorithms to create a model based on historical patient data and their responses to various medications. The goal is to predict the most effective drug for a new patient based on their specific attributes.
## About the Dataset
We've compiled data from patients who suffered from the same illness but responded to different medications: Drug A, Drug B, Drug C, Drug X, and Drug Y. The dataset includes attributes like Age, Sex, Blood Pressure, and Cholesterol levels, with the target being the drug that each patient responded to.

## Data Download
Data is sourced from a public repository and is essential for training our decision tree model.

## Pre-processing
The data undergoes several preprocessing steps to convert categorical variables into numerical formats suitable for the model, using encoding techniques.

## Setting up the Decision Tree
We use a train/test split approach to prepare our data for modeling. The Decision Tree is set up with parameters optimized for the best classification performance.

## Modeling
A DecisionTreeClassifier instance is created with an entropy criterion to maximize information gain. The model is trained on the preprocessed dataset.

## Prediction
The trained decision tree is used to make predictions on the testing set, aiming to accurately identify the appropriate drug based on patient data.

## Evaluation
Model performance is evaluated through accuracy metrics to assess the effectiveness of the decision tree in predicting the correct drug.

## Visualization
The structure of the trained decision tree is visualized to provide insights into the decision-making process of the model.
