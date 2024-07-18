# AI Mental Fitness Tracker 🌟🧠

This project focuses on predicting mental fitness using various machine learning algorithms. The dataset contains information about mental health disorders across different countries and years. The goal is to build a predictive model that can accurately estimate mental fitness based on the provided data.

## Steps 🚀

### 1. Data Loading and Processing 📂
The first step involves loading the required libraries and datasets. The data is loaded from two CSV files: `prevalence-by-mental-and-substance-use-disorder.csv` and `mental-and-substance-use-as-share-of-disease.csv`. These datasets are then merged into a single dataframe for further analysis. After merging, unnecessary columns are dropped, and the dataset is cleaned by handling missing values and renaming columns for better readability.

### 2. Exploratory Data Analysis (EDA) 🔍📊
EDA is performed to understand the data distribution and relationships between variables. This involves:

- Checking the first few rows of the dataset to understand its structure.
- Identifying and handling missing values.
- Renaming columns for clarity.
- Generating a correlation matrix to visualize the relationships between numeric variables.
- Creating visualizations such as heatmaps, pair plots, pie charts, and line plots to gain insights into the data.

### 3. Data Splitting ✂️
The dataset is split into training and testing sets. The feature set `X` includes all columns except the target variable `mental_fitness`, and the target variable `y` is `mental_fitness`. The data is split into training and testing sets using an 80-20 ratio.

### 4. Model Building and Training 🏗️🤖
Multiple machine learning algorithms are used to build predictive models. The following algorithms are employed:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- K-Nearest Neighbors (KNN)
- Support Vector Regression (SVR)
- Decision Tree Regressor

Each model is trained on the training set, and the performance is evaluated on both the training and testing sets using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.

### 5. Model Evaluation 📈
The models are evaluated based on their performance on the testing set. The following observations were made:

- Linear Regression: Achieved an accuracy of 98.27%.
- Random Forest Regressor: Achieved an accuracy of 99.37%.
- XGBoost Regressor: Achieved an accuracy of 98.96%.
- K-Nearest Neighbors (KNN): Achieved an accuracy of 98.45%.
- Support Vector Regression (SVR): Achieved an accuracy of 98.59%.
- Decision Tree Regressor: Achieved an accuracy of 99.14%.

The Random Forest Regressor performed the best, achieving an accuracy of 99.37% on the testing data.

## Contribution 🌟🤝
If you are interested in contributing to this repository, please feel free to fork the repository and create a pull request with your changes. Contributions can include improvements to the data processing, EDA, model training, or any other aspect of the project. Your contributions are greatly appreciated!

We hope you find this project helpful and insightful. Happy coding! 💻✨
