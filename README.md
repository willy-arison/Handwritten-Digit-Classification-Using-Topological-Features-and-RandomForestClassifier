# Handwritten Digit Classification Using Topological Features and RandomForestClassifier

## Description
This project focuses on classifying handwritten digits using topological features extracted from the MNIST dataset. The approach involves transforming the images into persistence diagrams using topological data analysis (TDA) techniques and then using these features to train a RandomForestClassifier. The project demonstrates the effectiveness of combining topological features with machine learning for image classification tasks.

## Key Features
- **Topological Data Analysis (TDA):** Utilizes persistence diagrams to capture the topological features of handwritten digits.
- **RandomForestClassifier:** A machine learning model trained on the extracted topological features to classify digits.
- **Confusion Matrix:** Evaluates the performance of the classifier, highlighting the most confused digits due to their topological similarities.

## Technologies Used
- Python
- Scikit-learn
- Giotto-tda (for TDA)
- Matplotlib (for visualization)
