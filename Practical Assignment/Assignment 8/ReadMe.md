# Decision Tree Classifier on Pima Indian Diabetes Dataset

## Overview

This project involves building a Decision Tree classifier using the Pima Indian Diabetes dataset. The tasks include:

- Downloading and loading the dataset.
- Feature selection separating dependent (target) and independent (feature) variables.
- Training a Decision Tree using scikit-learn.
- Visualizing the Decision Tree for interpretability.
- Calculating and analyzing Entropy, Information Gain, and Gini Index values to justify the choice of root node.

## Dataset

The Pima Indian Diabetes dataset contains medical diagnostic measurements used to predict diabetes presence in patients. The dataset includes the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (target variable: 0 or 1)

## Usage

1. Clone or download the repository.
2. Ensure the dataset file `diabetes.csv` is placed in the root directory.
3. Run the Jupyter notebook `Assignment-8.ipynb` for detailed analysis and decision tree modeling.

## Results

- The Decision Tree classifier is trained and visualized.
- The root node is selected based on max Information Gain / min Gini Index; analysis shows *Glucose* as the optimal root split.
- Detailed metrics for all features’ entropies, information gains, and Gini indices are provided to support root node selection.

## Technologies Used

- Python 3.x
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook

## GitHub Repository Link

[https://github.com/Aryanplux/Decision-Tree-Pima-Indian-Diabetes](https://github.com/Aryanplux/Statistical-Foundation-of-Data-Sciences/blob/main/Practical%20Assignment/Assignment%208/Assignment%208%20Statistical%20Foundation%20of%20Data%20Sciences.ipynb)

## Author

Aryan Dhiman  
Shoolini University  

---

*This project serves as an academic assignment for Statistical Foundation of Data Sciences.*


