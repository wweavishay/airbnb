# Airbnb Berlin Price Prediction Using Machine Learning

![Model Selection and Tuning](https://cdn-icons-png.flaticon.com/128/4494/4494647.png)  


## Project Overview

This project focuses on predicting Airbnb property prices in Berlin using various machine learning techniques. By analyzing historical price data and property features, we aim to develop a model that offers accurate price predictions. This can help property hosts set competitive rates and assist renters in finding the best deals.

## Data Preparation and Exploratory Data Analysis (EDA)

### Data Collection

The dataset used for this project is sourced from Kaggle's [Airbnb Berlin Ratings](https://www.kaggle.com/datasets/thedevastator/berlin-airbnb-ratings-how-hosts-measure-up).

### Data Cleaning and Structuring

- **Text Data:** Cleaned text fields by removing non-alphanumeric characters.
- **Categorical Variables:** Consolidated categories with excessive unique values into broader groups.

### Exploratory Data Analysis (EDA)

- **Statistics and Visualizations:** Generated basic statistics and visualizations to understand data distributions.
- **Sentiment Analysis:** Analyzed customer reviews to assess satisfaction.
- **Geographic Analysis:** Mapped property locations to identify location-based trends.




## Handling Missing Values

### Missing Values Treatment

- **Initial Imputation:** Filled missing values using K-Nearest Neighbors (KNN) imputation. KNN is effective for predicting missing values by leveraging the similarity between observations.
- **Record Removal:** Removed over 10,000 records with incomplete or unusable data.
- **Final Imputation:** Completed remaining missing values using Label Encoding to ensure data integrity and usability.

## Feature Engineering and Feature Selection

### Feature Engineering

- **Feature Importance:** Evaluated feature importance using Lasso, SVM with L1 penalty, Gradient Boosting, and Random Forest.

### Feature Selection

- **Model Aggregation:** Combined results from various models to finalize the dataset with the most relevant features.

![Feature Engineering](https://via.placeholder.com/600x300?text=Feature+Engineering)  
*Feature Engineering*  
*Width: 600px, Height: 300px*

## Model Selection and Fine-Tuning

### Model Selection

- **Algorithms Used:** Applied a combination of regression models, Random Forest, and Support Vector Machines (SVM) for price prediction.

### Fine-Tuning

- **Hyperparameter Optimization:** Employed Grid Search for hyperparameter tuning to maximize model accuracy.
- **Boosting:** Used Gradient Boosting to enhance model performance by sequentially building decision trees.

### Dataset Partitioning

- **Training and Testing Split:** Divided the dataset into 70% training and 30% testing, with further segmentation into low and high price categories.

![Model Selection and Tuning](https://via.placeholder.com/600x300?text=Model+Selection+and+Tuning)  
*Model Selection and Tuning*  
*Width: 600px, Height: 300px*

## Deployment and Impact

### Deployment

The model will be deployed via an API integrated with property management platforms, providing real-time price predictions and insights.

### Beneficiaries

- **Property Hosts:** Optimize pricing strategies to enhance earnings.
- **Renters:** Access accurate price predictions for informed decision-making.
- **Property Management Platforms:** Gain actionable market insights and improve user experience.

## Project Contributors

- **Avishay Aknin**
- **Bar Ilan University- Data Science Course**

## Conclusion

This project demonstrates the application of machine learning for predicting Airbnb property prices in Berlin. By understanding the key factors influencing prices and optimizing prediction accuracy, the model offers valuable tools for hosts, renters, and property management platforms.

---

