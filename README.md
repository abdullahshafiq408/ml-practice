# ML Practice Notebooks

A collection of hands-on machine learning practice notebooks 
covering core concepts from data preprocessing to model building. 
Each notebook is well-commented and written to demonstrate clear 
understanding of the underlying concepts.

## Topics Covered

- **Data Preprocessing** — missing value handling, encoding, 
  feature scaling, EDA, sklearn Pipelines

## Notebooks

| Notebook | Dataset | Concepts |
|---|---|---|
| `titanic_preprocessing.ipynb` | Titanic (Kaggle) | duplicates, missing values, outliers, scaling |
| `diabetes_preprocessing.ipynb` | Diabetes (sklearn) | duplicates, missing values, outliers, correlations, scaling |
| `feature_scaling.ipynb` | Sample Dataset | Absolute MinMax, MinMax, Standardization, Normalization, Robust |
| `feature_engineering.ipynb` | Sample Dataset | One-Hot Encoding, Binning, Feature Splitting |
| `exploratory_data_analysis.ipynb` | Sample Dataset | Data Cleaning, Univariate Analysis, Bivariate Analysis, Multivariate Analysis |
| `kfold_cross_validation.ipynb` | Iris Dataset | KFold Cross Validation, SVC, Results |
| `hyperparameter_tuning.ipynb` | Sample Dataset | GridSearchCV, LogisticRegression, RandomizedSearchCV, DecisionTree |
| `01_implementation_of_simple_linear_regression.ipynb` | Sample Dataset | Linear Regression, Gradient Descent |
| `02_simple_linear_regression.ipynb` | Sample Dataset | Simple Linear Regression |
| `03_multiple_linear_regression.ipynb` | California House Pricing | Multiple Linear Regression, 3D Visualization |
| `04_implementation_of_logistic_regression.ipynb` | Sample Dataset | Logistic Regression Using Numpy, Accuracy |
| `05_logistic_regression.ipynb` | Breast Cancer | Sklearn Logistic Regression, Accuracy |

## How to Run

```bash
git clone https://github.com/abdullahshafiq408/ml-practice
cd ml-practice
pip install -r requirements.txt
```

Open any notebook in Jupyter or Google Colab.

**Datasets:** Titanic is available on 
[Kaggle](https://www.kaggle.com/c/titanic). 
Diabetes dataset loads directly via `sklearn.datasets.load_diabetes()`.

## Tools & Libraries

Python · scikit-learn · Pandas · NumPy · Matplotlib · Seaborn · 
Jupyter

## Author

**Abdullah Shafiq** · Aspiring Machine Learning Engineer  
[LinkedIn](https://www.linkedin.com/in/abdullah-shafiq408) · 
[Portfolio](https://abdullahshafiq408.github.io/portfolio-website)
