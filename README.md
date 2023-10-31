# Kaggle-Credit-Risk-Analysis-for-Loans
📊 [View the Full Jupyter Notebook](https://github.com/Patrick-L-Taylor/Kaggle-Credit-Risk-Analysis-for-Loans/blob/main/bank-loan-credit-risk.ipynb)

## Table of Contents
- [Overview](#overview)
- [Datasets](#datasets)
- [Models Tested](#models-tested)
- [Key Takeaways](#key-takeaways)
- [Future Work](#future-work)
- [Acknowledgements](#acknowledgements)



## **Overview:**

In this project, we focus on predicting loan defaults using various machine learning models. By leveraging a dataset from Kaggle, we experimented with a diverse set of models to determine the most accurate and reliable approach for predicting default events.

## **Datasets:**

The dataset was sourced from Kaggle. It contains information on consumer defaults. There are eight feature columns and one column that signals if a default occurred or not. The features included are: Income, Work Experience, Education Level, Age of the Customers, Debt to Income Ratio, Credit to Debt ratio, Other debts & Address.

## **Models Tested:**

- Random Forest Classifier: A versatile model that constructs multiple decision trees during training and outputs the mode of the classes for classification or mean prediction of the individual trees for regression.
- Support Vector Machine (SVM): A representation of the examples as points in space, mapped so that the categories are divided by a clear gap that is as wide as possible.
- Logistic Regression: A statistical method for modeling the likelihood of a particular outcome based on one or more predictors.
- Bagging Classifier: An ensemble meta-estimator that fits base classifiers on random subsets of the original dataset and then aggregates their individual predictions to form a final prediction.
- AdaBoosted Classifier: An adaptive boosting ensemble classifier that constructs a classifier by fitting copies of a weak learner on repeatedly modified versions of the data.
- Voting Classifier: An ensemble meta-estimator which aggregates predictions from multiple fitted classifiers.
- Stacked Classifiers: An ensemble-learning meta-classifier for stacking which uses predictions from multiple trained classifiers and uses another classifier to combine these predictions to predict the class labels of the samples.

## **Key Takeaways:**

The Support Vector Machine and AdaBoost models performed the best in terms of mean accuracy, indicating their robustness for this specific problem.
The Voting Classifier was particularly notable, as it leveraged the power of underlying models like SVM and AdaBoost to achieve the same top-tier performance.

## **Future Work:**

- Experiment with more advanced feature engineering techniques to possibly improve the model performance.
- Test the models on newer, more extensive datasets to check the robustness of the current findings.
- Explore deep learning models, which might be overkill for the current dataset but could be beneficial for larger datasets.

## **Acknowledgements:**

This project was inspired by a Kaggle project. 

Here is the link for the Kaggle Project Page: https://www.kaggle.com/datasets/atulmittal199174/credit-risk-analysis-for-extending-bank-loans/data

