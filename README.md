# Titanic-Survival-Prediction

## 🚢 Titanic Survival Prediction with Random Forest
This is my first Machine Learning project where I predict the survival of passengers aboard the Titanic using a Random Forest Classifier. 🌳✨

## 📚 Project Overview
Dataset: Titanic - Machine Learning from Disaster (Kaggle)

Goal: Predict whether a passenger survived or not based on features like age, sex, passenger class, etc.

Algorithm Used: Random Forest Classifier

## 🛠️ Technologies Used
Python 3

Jupyter Notebook

pandas

numpy

matplotlib

seaborn

scikit-learn

## 📂 Project Steps
Data Loading

Loaded the dataset into a pandas DataFrame.

Data Cleaning

Filled missing Age values with the mean age.

Filled missing Embarked values with the most frequent port.

Dropped unnecessary columns like Cabin, Ticket, and Name.

Exploratory Data Analysis (EDA)

Visualized relationships between features (like Sex and Pclass) and survival.

Feature Engineering

Used Label Encoding to convert categorical variables into numeric.

Model Training

Built a Random Forest model with n_estimators = 100.

Trained it on the training dataset.

Model Evaluation

Achieved around 73% accuracy on the test set.

Observed that increasing n_estimators can sometimes improve stability.

## 🎯 Key Learnings
How Random Forest reduces overfitting by combining multiple decision trees.

How missing data handling and feature encoding impact model performance.

Importance of balancing model complexity and computation time.

## 📈 Results

Metric	Value
Final Accuracy	~73%
⚡ Future Improvements
Hyperparameter tuning (e.g., max_depth, min_samples_split).

Feature extraction (like getting titles from names).

Trying other algorithms like Logistic Regression, SVM, or XGBoost.

## 📢 Connect with Me!
I'm excited to keep learning and building! Feel free to connect or collaborate:

LinkedIn: https://www.linkedin.com/in/yuvaraj-s-901237248/

GitHub: https://github.com/Yuva1024

## 📝 License
This project is open for educational purposes.

# 🙌 Thanks for checking out my project!
