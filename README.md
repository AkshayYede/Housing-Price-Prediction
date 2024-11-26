# Housing-Price-Prediction
## **Housing Price Prediction with Machine Learning**

### **Project Overview**
This project aims to predict housing prices in California using various machine learning algorithms. The dataset used contains features such as **median income**, **total rooms**, **total bedrooms**, **population**, **ocean proximity**, and other factors that influence house prices. The goal is to build a predictive model that can estimate the **median house value** based on these input features.

### **Objective**
The objective of this project is to predict the **median house value** for California districts. This is a regression problem where the target variable is continuous (house price). The project covers:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Hyperparameter tuning

### **Dataset**
The dataset is sourced from the **California Housing dataset**, which contains the following columns:
- **longitude**: Longitude of the district
- **latitude**: Latitude of the district
- **housing_median_age**: The median age of houses within the district
- **total_rooms**: Total number of rooms in all houses in the district
- **total_bedrooms**: Total number of bedrooms in the district
- **population**: The population of the district
- **households**: The number of households in the district
- **median_income**: The median income of households in the district
- **median_house_value**: The target variable — median house value in the district
- **ocean_proximity**: The proximity of the district to the ocean (categorical feature)

### **Dependencies**
The following libraries are required to run this project:
- **Python** (version 3.x)
- **pandas**: For data manipulation and analysis
- **numpy**: For numerical operations
- **matplotlib**: For data visualization
- **seaborn**: For statistical data visualization
- **scikit-learn**: For machine learning models, preprocessing, and evaluation
- **joblib**: For saving and loading models

**Model Evaluation:**
   The project uses multiple machine learning models, including **Linear Regression**, **Decision Trees**, and **Random Forest Regressor** to predict housing prices. The performance of each model is evaluated using **Mean Squared Error (MSE)** and **cross-validation**.

### **Features**
- **Data Preprocessing**: Handling missing values, feature scaling, and encoding categorical variables.
- **Exploratory Data Analysis (EDA)**: Visualizing relationships between features, identifying outliers, and understanding distributions.
- **Machine Learning Models**: Training multiple regression models and evaluating their performance.
- **Hyperparameter Tuning**: Using **RandomizedSearchCV** and **GridSearchCV** to optimize model performance.

### **Evaluation Metrics**
The primary evaluation metric used in this project is **Mean Squared Error (MSE)**. The lower the MSE, the better the model’s predictions match the actual house prices. Cross-validation is also performed to ensure the model generalizes well on unseen data.
