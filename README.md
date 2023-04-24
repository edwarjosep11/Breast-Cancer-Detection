# Breast Cancer Detection

This project aims to build machine learning models to predict breast cancer based on features such as age, tumor size, and number of positive lymph nodes. The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Dataset from the UCI Machine Learning Repository. The data is available at [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data?datasetId=180&sortBy=voteCount).

## Files 
* [Breast-Cancer-Prediction](): Jupyter Notebook with full code and the results of each model. 
* README.md: A markdown file that contains information about the project.

## Dataset
The dataset consists of 569 instances and 30 features. The target variable is a binary classification of malignant or benign breast cancer. The features include:

> **diagnosis**: The diagnosis of the breast mass cells as either malignant (M) or benign (B).<br>
**radius_mean**: The mean radius of the breast mass cells.<br>
**texture_mean**: The mean texture (standard deviation of gray-scale values) of the breast mass cells.<br>
**perimeter_mean**: The mean perimeter of the breast mass cells.<br>
**area_mean**: The mean area of the breast mass cells.<br> **etc...**

## Models

Several machine learning models were trained and evaluated on the dataset, including:

* Logistic Regression.
* Random Forest Classifier.
* K-Nearest Neighbors (KNN) Classifier.
* XGBoost.
* Support Vector Machine (SVM).

## Results

The models were evaluated using 10-fold cross-validation and the accuracy metric. The results are as follows:

* Logistic Regression: 95.4%
* Logistic Regression + CV: 95.4%
* Random Forest Classifier: 94.6%
* KNN Classifier: 93.9%
* **XGBoost: 95.9% (Winner)**
* SVM: 94.4%

Based on the accuracy results, the XGBoost model performed the best on the dataset.

## Next Steps
* Conduct feature selection to identify the most important features for breast cancer prediction.
* Tune the hyperparameters of the models to improve their performance.
* Collect more data to improve the accuracy of the models.
* Deploy the best-performing model as a web application for breast cancer prediction.

## Credits
* [Fares Sayah](https://www.kaggle.com/code/faressayah/support-vector-machine-pca-tutorial-for-beginner).
* [Anandhu H](https://www.kaggle.com/code/anandhuh/breast-cancer-prediction-accuracy-98-24/notebook).
* [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data?datasetId=180&sortBy=voteCount).


