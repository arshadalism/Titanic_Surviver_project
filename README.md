🚢 Titanic Survival Prediction

Predicting survival on the Titanic using Machine Learning 🚀

📌 Project Overview

The Titanic dataset is one of the most popular beginner datasets for Machine Learning.
In this project, we build and evaluate multiple ML models to predict whether a passenger survived or not, based on features such as age, gender, class, and family size.

This project demonstrates the end-to-end ML pipeline:

Data cleaning & preprocessing

Exploratory data analysis (EDA)

Feature engineering

Model training & evaluation

Predictions & Kaggle submission

📂 Dataset

The dataset is provided by Kaggle - Titanic: Machine Learning from Disaster.

train.csv → training dataset with survival labels

⚙️ Technologies Used

Python 3.x

Pandas, NumPy → data manipulation

Matplotlib, Seaborn → data visualization

Scikit-Learn → machine learning models

Jupyter Notebook → development environment

📊 Exploratory Data Analysis (EDA)

Some insights from the data:

Women had a much higher chance of survival than men.

Passengers in 1st class had higher survival rates than those in 2nd or 3rd class.

Younger passengers tended to survive more often than older ones.

(Visualizations included in the notebook)

🛠️ Project Workflow

Data Preprocessing

Handle missing values (Age, Embarked, Fare)

Encode categorical variables (Sex, Embarked)

Drop irrelevant features (Ticket, Cabin, Name)

Feature Engineering

FamilySize = SibSp + Parch + 1

IsAlone → whether passenger was traveling alone

Model Training

Logistic Regression

Random Forest

(Optional: XGBoost, LightGBM, SVM)

Evaluation

Accuracy, Precision, Recall, F1-score

Confusion Matrix

Prediction & Submission

Generate submission.csv for Kaggle

📈 Results

Random Forest Classifier achieved the best validation accuracy (~80-82%).
