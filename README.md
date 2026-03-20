# Assignment

Problem Statement

The objective of this project is to build a machine learning model that predicts student exam scores based on various input features such as study hours and attendance. The goal is to understand how different factors influence student performance.

📂 Dataset Description

A custom dataset was created using a Pandas DataFrame with a minimum of 15 records.
The dataset includes the following features:

Study Hours (Input Feature)

Attendance Percentage (Input Feature)

Exam Score (Target Variable)

Additional feature engineering was also performed to improve model performance.

🤖 Model Used

A Linear Regression model was implemented using the Scikit-learn library.
The dataset was split into training and testing sets to evaluate model performance effectively.

📈 Results

Mean Absolute Error (MAE) was calculated to measure prediction accuracy.

R² Score was used to evaluate how well the model fits the data.

The model showed reasonable performance, indicating a relationship between input features and exam scores.

Feature experiments were conducted:

Removing a feature reduced model performance.

Adding a meaningful feature improved predictions.

⚠️ Overfitting Analysis

The model was also trained on the full dataset without splitting.
This resulted in better performance metrics but did not reflect real-world accuracy.
This demonstrates overfitting, where the model memorizes data instead of learning patterns.

✅ Conclusion

This project demonstrates the implementation of a basic machine learning pipeline using Linear Regression.
It highlights the importance of feature selection, proper evaluation techniques, and avoiding overfitting.
The results show that input features significantly impact prediction accuracy.
