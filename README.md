🏥 Insurance Cost Prediction Using Machine Learning

📌 Project Overview

This project focuses on predicting medical insurance charges using Machine Learning techniques. It uses demographic and health-related features to estimate insurance costs with a Linear Regression model.

The project demonstrates the complete Machine Learning workflow, from Exploratory Data Analysis (EDA) and data preprocessing to feature selection, model training, and evaluation.

🎯 Objectives

- Explore and understand the insurance dataset.
- Clean and preprocess the data.
- Perform feature engineering and categorical encoding.
- Analyze relationships between features and insurance charges.
- Train a Linear Regression model.
- Evaluate model performance using R² and Adjusted R².

📊 Dataset Description

The dataset contains the following features:

Feature| Description
"age"| Age of the individual
"sex"| Gender of the individual
"bmi"| Body Mass Index
"children"| Number of dependent children
"smoker"| Whether the individual smokes
"region"| Residential region
"charges"| Medical insurance charges (target variable)

Target Variable: "charges"

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

🔍 Project Workflow

1. Exploratory Data Analysis (EDA)

- Explored the dataset and its features.
- Examined data distributions.
- Used visualizations to understand patterns in the data.

2. Data Cleaning and Preprocessing

- Created a copy of the original dataset.
- Removed duplicate records.
- Checked for missing values.
- Examined data types.
- Encoded categorical variables.
- Renamed columns for better readability.
- Applied One-Hot Encoding to categorical features.

3. Feature Engineering

- Created BMI categories using "pd.cut()".
- Categorized BMI into:
  - Underweight
  - Normal
  - Overweight
  - Obese
- Converted categorical features into numerical representations.

4. Feature Scaling

- Used "StandardScaler" to standardize selected numerical features.
- Studied the importance of feature scaling in Machine Learning.

5. Statistical Analysis and Feature Selection

Pearson Correlation

- Examined linear relationships between numerical features and insurance charges.

Chi-Square Test

- Tested associations between categorical features and categorized insurance charges.
- Used a significance level of 0.05.
- Compared p-values to assess statistical significance.

6. Model Training

- Separated independent variables ("X") and the target variable ("y").
- Split the dataset into training and testing sets.
- Used an 80:20 train-test split.
- Trained a Linear Regression model using Scikit-learn.

7. Model Evaluation

Evaluated the model using:

- R² Score: Measures the proportion of target-variable variance explained by the model.
- Adjusted R²: Accounts for the number of predictors relative to the sample size.

The notebook reported an Adjusted R² of approximately 0.798.

Note: This is the result of the current notebook workflow. The evaluation should be repeated after correcting preprocessing and data leakage issues.

🤖 Machine Learning Algorithm

Linear Regression

Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values.

In this project, it is used to estimate medical insurance charges based on selected features.

📁 Project Structure

Insurance-Project/
│
├── Insurance.ipynb
├── README.md
├── app.py
├── insurance_model.pkl
└── requirements.txt

"app.py", "insurance_model.pkl", and "requirements.txt" are intended for the planned web deployment and should be added when they have been created and tested.

🚀 Future Improvements

- Correct preprocessing and prevent data leakage.
- Use a Scikit-learn Pipeline to combine preprocessing and model training.
- Evaluate additional regression algorithms.
- Compare MAE, RMSE, R², and Adjusted R².
- Develop an interactive web application using Streamlit.
- Deploy the application online.

📚 Key Learnings

Through this project, I practiced:

- Data cleaning and preprocessing.
- Categorical encoding.
- Feature engineering.
- Feature scaling.
- Statistical hypothesis testing.
- Feature selection.
- Linear Regression.
- Train-test splitting.
- Regression model evaluation.

👨‍💻 Author

Vishnu Mishra

B.Tech Student | Aspiring Data Analyst

---

⭐ This project is part of my hands-on learning journey in Data Analytics and Machine Learning.
