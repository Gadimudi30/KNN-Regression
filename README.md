# KNN Regression

## California Housing Price Prediction

### Project Overview
This project focuses on implementing the **K-Nearest Neighbors (KNN) Regression** algorithm using the California Housing Prices dataset. The main objective is to predict median house values based on different housing-related features.

I performed data preprocessing, trained the KNN Regression model, evaluated its performance and compared different distance metrics to understand how they affect prediction results.

### Objectives
- Understand and implement the KNN Regression algorithm.
- Explore and analyze the California Housing Prices dataset.
- Handle missing values and categorical variables.
- Apply feature scaling using StandardScaler.
- Split the dataset into training and testing sets.
- Train a KNN Regression model.
- Evaluate model performance using regression metrics.
- Compare different distance metrics.
- Predict house values for new, unseen data.

### Dataset Information
**Dataset:** California Housing Prices

The dataset contains information about houses in different areas of California.

**Dataset details:**
- Total records: 20,640
- Total columns: 10
- Target variable: `median_house_value`

**Important features:**
- `longitude` – Geographic longitude of the area.
- `latitude` – Geographic latitude of the area.
- `housing_median_age` – Median age of houses.
- `total_rooms` – Total number of rooms.
- `total_bedrooms` – Total number of bedrooms.
- `population` – Population of the area.
- `households` – Number of households.
- `median_income` – Median income of the area.
- `ocean_proximity` – Distance category relative to the ocean.
- `median_house_value` – Median house value (target variable).

### Technologies and Libraries Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Project Workflow

**1. Data Loading**
- Loaded the dataset using Pandas.
- Displayed the first and last few records.

**2. Data Exploration**
- Checked dataset shape, columns and data types.
- Generated statistical summaries.
- Identified missing values and duplicate records.

**3. Data Preprocessing**
- Handled missing numerical values using median imputation.
- Handled categorical values using most frequent imputation.
- Converted categorical data using One-Hot Encoding.
- Standardized numerical features using StandardScaler.

**4. Train-Test Split**
- Divided the dataset into 80% training data and 20% testing data.

**5. Model Building**
- Implemented the KNN Regression algorithm using `KNeighborsRegressor`.
- Used 5 nearest neighbors to make predictions.

**6. Model Evaluation**
Evaluated the model using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

**7. Distance Metric Comparison**
Compared three distance metrics:
- Minkowski
- Manhattan
- Chebyshev

**8. Prediction**
Tested the trained model using a new unseen house record to predict its median house value.

### Results and Analysis
The model performance was evaluated using different regression metrics. The three distance metrics were compared to understand their impact on prediction accuracy.

The best-performing distance metric was identified based on the evaluation results.

The model was also tested with a new house record to generate a continuous numerical prediction.

### Key Learnings
- Understood the working principle of KNN Regression.
- Learned how to handle missing values and categorical variables.
- Understood the importance of feature scaling in distance-based algorithms.
- Learned how to split data into training and testing sets.
- Practiced evaluating regression models using different metrics.
- Understood the impact of different distance metrics on model performance.

### Conclusion
Through this task, I gained practical experience in implementing the KNN Regression algorithm using Python. I learned how to preprocess real-world data, train a regression model, evaluate its performance and predict house values for new data.

This task helped me improve my understanding of machine learning concepts and regression-based prediction techniques.

### Project Structure

KNN-Regression/
│
├── Daily_Task_2_KNN_Regression.ipynb
├── housing.csv
└── README.md
