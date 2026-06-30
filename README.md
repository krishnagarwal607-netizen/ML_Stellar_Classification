# Stellar Classification using Machine Learning

## About the Project

The objective is to classify celestial objects into three categories—**GALAXY**, **STAR**, and **QSO (Quasi-Stellar Object)**—using machine learning algorithms.

The project covers the complete machine learning workflow, starting from data preprocessing and exploratory data analysis to model training, hyperparameter tuning, and final model evaluation.

---

## Dataset

The dataset contains **100,000 observations** with **18 columns**, including the target variable (`class`).

The features include photometric measurements, redshift, and observational metadata collected from the Sloan Digital Sky Survey (SDSS).

---

## Project Workflow

* Data loading
* Data cleaning and preprocessing
* Feature selection
* Exploratory Data Analysis (EDA)
* Train-test split
* Feature scaling
* Training and evaluation of:

  * Logistic Regression
  * Decision Tree
  * Random Forest
* Feature importance analysis
* Principal Component Analysis (PCA)
* Hyperparameter tuning using GridSearchCV
* Training the optimized Random Forest model
* Final model evaluation using:

  * Accuracy
  * Classification Report
  * Confusion Matrix
  * ROC-AUC Curve

---

## Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Model Results

Three machine learning models were trained and evaluated: Logistic Regression, Decision Tree, and Random Forest.

Among them, the **Random Forest** classifier achieved the best performance. After tuning its hyperparameters using **GridSearchCV**, the final model achieved a test accuracy of approximately **97.8%**.

The confusion matrix showed that most samples were classified correctly with very few misclassifications. The ROC-AUC curves for all three classes were close to the top-left corner, indicating that the model is able to distinguish well between galaxies, stars, and quasars.

Overall, the tuned Random Forest model provided the best balance of accuracy and generalization for this classification task.

---

## Repository Contents

* `Stellar_Classification.ipynb` – Complete notebook containing the implementation
* `star_classification.csv` – Dataset used in the project
* `README.md` – Project documentation

---

## Setup Instructions

1. Clone this repository.
2. Make sure Python 3 is installed.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open the notebook using Jupyter Notebook or Google Colab.
5. Run all the cells from top to bottom.



---

## Author

**Krishna Agarwal**
