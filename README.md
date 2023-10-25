# Data Analysis and Classification Project

## Project Description

The aim of this project was to analyze and classify data related to websites in the context of identifying malicious websites (malware). We employed various data processing techniques and classifiers, including Random Forest, XGBoost, and K-Nearest Neighbors (KNN), to achieve the best results in class prediction.

## Data Preparation

In this project, we initially conducted data analysis, including cleaning and data transformation, to remove missing values and convert non-numeric values into numeric ones. Ultimately, we prepared the dataset for training and model evaluation.

## Model Experiments

1. **Random Forest Classifier:** This model achieved high overall accuracy (0.9923) on training and test data. Accuracy and precision in class classification were satisfactory. However, the detection of real malware cases (class 1) left room for improvement.

2. **XGBoost Classifier:** The XGBoost model also achieved high accuracy (0.9904) on training and test data. There were differences in precision and recall for different classes, and malware detection had some room for enhancement.

3. **K-Nearest Neighbors (KNN) Classifier:** KNN achieved an accuracy of 0.9896, with higher precision in classifying class 0 but relatively lower recall in classifying malware.

## Model Evaluation

During the model evaluation, we performed an analysis of precision, recall, F1-score, and ROC and PR curves. The choice of the best model depends on the specific application and the importance of different parameters, such as precision and recall.

## Results and Conclusions

In the context of "production data" (data that was not available during training), we suggest that the choice of the model depends on the nature of the data and the significance of precision and recall in the given context. Optimizing models and increasing training data with the malware class can significantly improve results.

Additionally, better data preprocessing, especially addressing inconsistent data formats across columns and handling misleading information, could lead to better outcomes in identifying malicious websites.

## System Requirements

* Python (version >= 3.7)
* Python libraries: numpy, pandas, scikit-learn, xgboost, matplotlib, seaborn
