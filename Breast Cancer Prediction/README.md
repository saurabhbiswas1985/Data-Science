# Breast Cancer Prediction by Machine Learning
## Introduction
Breast Cancer is the 2nd most common cancer in women. But, on rare scenario can also happen to men. It is 2nd leading cause of deaths of women after lung cancer. A fine needle biopsy is an effective tool in evaluating and diagnosing suspect lumps or masses. With early diagnosis of breast cancer, patients can be isolated for early treatment for a better chance of survival.
Early detection of disease has become a crucial problem due to rapid population growth in medical research in recent times.

My aim is to develop a **classification model** that will identify breast cancer using the FNA diagnosis label with **higher accuracy**. This model will be great for **predicting cancer in advance**, because classification algorithms make boundaries between data points classifying them as a certain group, depending on their characteristics matched against the model’s parameters.

## Data Used
* Dataset: [Creditcard Fraud Dataset](https://www.kaggle.com/isaikumar/creditcardfraud)
* Highly **imbalanced Dataset**. Out of 284807 total transactions only 492 transactions are fraudulent i.e. it represents only 0.17% of the entire dataset.
* To maintain the data confidentiality, most of the variables (V1 through V28) were PCA transformed.
## Technology Used
* Python 3
* Jupyter Notebook on Anaconda
## Method Used
* Pandas Profiling for initial Data Exploration.
* Find input features that are most correlated to output class.
* Boxplot to detect & remove outlier.
* Set **Pipeline** to do data transformation using **ColumnTransformer** and **RobustScaler**.
* Average Precision is used for matrix evaluation.
* **GridSearchCV** is used to tune Random Forest, Logistic Regression and Artificial Neural Network Classifier parameters and select the best one.
* Best model's performance test and evaluation.
## Potential Issues
* Dataset is highly imbalanced. This may create problems for model training.
* V1,..,V28 are PCA transformed. No way to carry out visualization for these fields.
* Limited training data may not fully converge ANN model.
## Future Scope
* Random Forest classifier needs to be **calibrated** to achieve good result.
* **Oversampling** the minority class would address imbalance dataset problem.
* Keeping these models **up to date** using latest fraud data is required.
## Reference
* [Artificial Neural Network](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html)
* [Credit Card Fraud Statistics](https://shiftprocessing.com/credit-card-fraud-statistics/)

[Go Back](https://saurabhbiswas1985.github.io/Data-Science/)
