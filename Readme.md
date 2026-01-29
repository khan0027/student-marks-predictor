# Student Score Prediction using Linear Regression

## Project Overview
This is a beginner-level Machine Learning project that uses **Linear Regression** to predict a student's exam score based on the number of hours studied.

The project focuses on understanding the basic machine learning workflow including data loading, visualization, model training, and prediction.

---

## Problem Statement
Predict the marks obtained by a student based on the number of hours they studied.

---

## Project Structure
student-score-prediction/
│
├── data.csv
├── model.py
├── visualization.py
└── README.md

---

## Dataset Description
The dataset contains two columns:
- Hours: Number of hours studied
- Score: Marks obtained in the exam

The data is suitable for applying simple linear regression.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Machine Learning Algorithm
Linear Regression

The model follows the equation:
Score = (weight × Hours) + bias

---

## How to Run the Project

1. Install required libraries:
pip install pandas matplotlib scikit-learn

2. Run the model file:
python model.py

3. Enter the number of hours studied when prompted.

---

## Sample Output
Enter number of hours studied: 6  
Predicted score for 6 hours of study is: 71.34

---

## Visualization
A scatter plot and regression line are used to visualize the relationship between hours studied and exam score.


---

## Future Improvements
- Add train-test split
- Calculate Mean Squared Error and R² score
- Implement linear regression from scratch
- Add more input features
- Convert the project into a web application

---

## Author
Md Saqulain  
Aspiring Machine Learning Engineer
