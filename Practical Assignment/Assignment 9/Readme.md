# Iris Classification with K-Nearest Neighbors (KNN)

## Overview

This project demonstrates step-by-step classification of the classic Iris dataset using K-Nearest Neighbors (KNN). It includes exploratory data analysis (EDA), data preprocessing, model training, hyperparameter (K) tuning, and thorough performance visualization.

---

## Dataset

- **Source:** [sklearn.datasets.load_iris](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
- **Features:** Sepal length, Sepal width, Petal length, Petal width
- **Classes:** Setosa, Versicolor, Virginica (3 total, labeled as 0/1/2)

---

## Workflow Steps

1. **Data Exploration:**  
   - Display head, describe, and group means by class.
2. **Feature Scaling:**  
   - Standardize features for fair distance measurements.
3. **Train/Test Split & Model Training:**  
   - Fit KNN classifier (`n_neighbors=5` initially) on train set.
4. **Evaluation:**  
   - Confusion matrix and accuracy score.
5. **Classification Report:**  
   - Precision, recall, F1-score per class.
6. **K-Value Optimization:**  
   - Loop from k=1..20, plot error rates to find optimal K.
7. **Visualization:**  
   - Scatterplot of two features showing test predictions versus true labels.

---

## Key Libraries Used

| Library        | Purpose                                   |
|----------------|-------------------------------------------|
| pandas         | Data handling, EDA                        |
| numpy          | Array computations                        |
| matplotlib     | Visualization                             |
| seaborn        | Statistical plots                         |
| scikit-learn   | Dataset, scaling, modeling, metrics       |

---

## Quick Start

git clone https://github.com/Aryanplux/Statistical-Foundation-of-Data-Sciences.git
cd Statistical-Foundation-of-Data-Sciences
pip install -r requirements.txt
jupyter notebook Assignment-KNN-Iris.ipynb

---

## Results & Insights

- **Best K:** Chosen via lowest error rate from k loop
- **Accuracy:** High accuracy reported for optimal K
- **Class Performance:** Detailed per-class results via classification report
- **Visualization:** Test predictions visually compared, misclassifications highlighted

---

## How to Customize

- Change tested features in scatterplots for different perspectives.
- Adjust data split ratio for robustness checks.
- Experiment with other classifiers (SVM, Decision Tree, etc.) for comparisons.

---

## License

Distributed under the MIT License.  
For academic purposes and reproducible research.

---

## Author

**Aryan Dhiman**  
CSU1658 – Statistical Foundation of Data Sciences  
Shoolini University

---

## Repository

[https://github.com/Aryanplux/Statistical-Foundation-of-Data-Sciences](https://github.com/Aryanplux/Statistical-Foundation-of-Data-Sciences)

---

## Contact

- Email: aryandhiman@shooliniuniversity.com
- LinkedIn: [Aryan Dhiman](https://www.linkedin.com/in/aryan-dhiman-a8974628b/)

