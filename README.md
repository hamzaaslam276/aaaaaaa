# Decision Tree Classifier on Iris Dataset

## Overview
This project implements a Decision Tree Classifier to classify the species of the famous Iris dataset. The model is trained using the `scikit-learn` library and evaluated for accuracy and performance. Additionally, the decision tree is visualized using `matplotlib`.

## Dataset
The Iris dataset consists of 150 samples with four features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

There are three classes (species) in the dataset:
- Setosa (0)
- Versicolor (1)
- Virginica (2)

## Project Workflow
1. Load the Iris dataset using `scikit-learn`.
2. Convert the dataset into a Pandas DataFrame for better visualization.
3. Split the dataset into training (80%) and testing (20%) sets.
4. Train a `DecisionTreeClassifier` on the training data.
5. Evaluate the model using accuracy and a classification report.
6. Visualize the decision tree.

## Installation
Ensure you have Python and the necessary libraries installed:
```bash
pip install pandas scikit-learn matplotlib
```

## Usage
Run the script to train the Decision Tree Classifier and display the evaluation results:
```bash
python decision_tree_iris.py
```

## Model Evaluation
- Accuracy: 100% on the test dataset
- Classification report confirms perfect precision, recall, and F1-score

## Decision Tree Visualization
The trained decision tree is plotted and saved as a high-resolution TIFF image (`tiff_compressed.tiff`).

## Output Example
```
Accuracy: 1.0
Classification Report:
              precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30
```

## Visualization
The decision tree diagram shows the classification process based on the feature splits.

![Decision Tree](tiff_compressed.tiff)

