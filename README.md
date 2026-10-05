# Machine Learning

A collection of Jupyter notebooks implementing classic machine learning algorithms with **scikit-learn**, from data preprocessing through regression and classification models.

## Contents

### Data Preprocessing
| Notebook | Description |
|---|---|
| [Preprocessing](Preprocessing.ipynb) | Missing values (`SimpleImputer`), categorical encoding (`OneHotEncoder`, `LabelEncoder`), train/test split, feature scaling |

### Regression
| Notebook | Model | Dataset |
|---|---|---|
| [Simple Linear Regression](SimpleLinearRegression.ipynb) | `LinearRegression` | Salary_Data |
| [Multiple Linear Regression](MultipleLinearRegression.ipynb) | `LinearRegression` + one-hot encoding | 50_Startups |
| [Polynomial Regression](PolynomialRegression.ipynb) | `PolynomialFeatures` + `LinearRegression` | Position_Salaries |
| [Support Vector Regression](SupportVectorRegression.ipynb) | `SVR` | Position_Salaries |
| [Decision Tree Regression](DecisionTreeRegression.ipynb) | `DecisionTreeRegressor` | Position_Salaries |
| [Random Forest Regression](RandomForestAlgorithm.ipynb) | `RandomForestRegressor` | Position_Salaries |

### Classification
| Notebook | Model | Dataset |
|---|---|---|
| [Logistic Regression](LogisticRegression.ipynb) | `LogisticRegression` | Social_Network_Ads |
| [K-Nearest Neighbors](KNN.ipynb) | `KNeighborsClassifier` | Social_Network_Ads |
| [Support Vector Machine](SupportVectorMachine.ipynb) | `SVC` (linear) | Social_Network_Ads |
| [SVM – RBF Kernel](SVM-RBFKernel.ipynb) | `SVC` (RBF kernel) | Social_Network_Ads |
| [Naive Bayes](NaiveBayes.ipynb) | `GaussianNB` | Social_Network_Ads |
| [Decision Tree Classification](DecisionTree.ipynb) | `DecisionTreeClassifier` | Social_Network_Ads |
| [Random Forest Classification](RandomForestClassification.ipynb) | `RandomForestClassifier` | Social_Network_Ads |

Classification models are evaluated with accuracy score and confusion matrices.

## Tech Stack
- Python
- NumPy, Pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

## Running
```bash
pip install numpy pandas matplotlib scikit-learn jupyter
jupyter notebook
```
The notebooks expect the CSV datasets in a `Python/` folder next to them.
