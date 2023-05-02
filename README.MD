# Springleaf Direct Mail Marketing Response Project
This project aims to predict which customers are likely to respond to Springleaf's direct mail marketing campaign for personal and auto loans. The project uses a large dataset of anonymized customer features and applies machine learning techniques to construct new meta-variables and select the most important features for prediction. The project uses Python and popular machine learning libraries such as pandas, scikit-learn, and XGBoost.

## **Dataset**
The dataset contains over 1 million observations and over 1,800 anonymized features. The dataset is provided by Springleaf and is available on Kaggle [here](https://www.kaggle.com/c/springleaf-marketing-response/data).

## **Approach**
The project takes the following approach:

1. **Data cleaning and preprocessing**: We started by exploring and cleaning the dataset, which involved handling missing values, encoding categorical variables, and converting data types.

2. **Exploratory Data Analysis (EDA)**: We performed EDA to better understand the data and identify any patterns or insights. We used various data visualization techniques such as histograms, bar charts, and line graphs to visualize the distributions and relationships between variables.

3. **Feature engineering**: We created new variables based on domain knowledge and exploratory analysis to potentially improve model performance.

4. **Feature selection**: We used different methods such as correlation analysis and recursive feature elimination to select the most relevant variables for modeling.

5. **Model selection**: We tested several machine learning algorithms, including **logistic regression, random forest, and XGBoost**, to find the one with the best performance. We also performed hyperparameter tuning with grid search to optimize the chosen algorithm.

6. **Evaluation**: We evaluated model performance using various metrics such as accuracy, precision, recall, and F1-score. 

7. **Next steps**: There are several areas for future improvement, such as better feature engineering, more hyperparameter tuning, and potentially using autoML to identify the best model automatically. It would also be beneficial to gain a better understanding of the features, despite their anonymization, to further improve the model.

## **Results**
The project achieves a final **F1 score** of **0.87** using **XGBoost** after hyperparameter tuning. The model is able to predict with a high degree of accuracy which customers are likely to respond to Springleaf's direct mail marketing campaign.

## **Conclusion**
Overall, this project demonstrates the effectiveness of machine learning techniques in predicting which customers are likely to respond to Springleaf's direct mail marketing campaign. The project also highlights the challenges of dealing with large amounts of data and the need for careful feature engineering and model selection.