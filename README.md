# TASK-2 Predictive Analysis Using Machine Learning
Data Analytics Internship Projects at CodTech IT Solutions  
Project Name - Student Pass/Fail Prediction Using Machine Learning

---

## 📋 Internship Details

| Field | Details |
|-------|---------|
| **Name** | Akshra |
| **Company** | CODTECH IT Solutions Pvt. Ltd |
| **Intern ID** | CTISO5S9 |
| **Domain** | Data Analytics |
| **Duration** | 4 weeks |
| **Mentor** | Neela Santhosh Kumar |
| **Task** | Task 1 — Big Data Analysis |

---


🎓 Project Title

Student Pass/Fail Prediction Using Machine Learning

---

📌 Project Overview

This project aims to predict whether a student will pass or fail using Machine Learning classification techniques based on multiple academic and demographic features such as study hours, attendance rate, previous scores, parental education, internet access, extracurricular activities, and more.

The project is developed using Logistic Regression and Random Forest Classifier, supervised Machine Learning algorithms widely used for classification and predictive analysis. The workflow includes data preprocessing, feature engineering, visualization, model training, prediction, and evaluation.

---

🎯 Objective

To build a Machine Learning model capable of accurately predicting student pass/fail outcomes using various academic performance indicators and student background attributes.

---

🛠️ Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

📂 Dataset Features

The dataset contains the following features:

- StudentID → Unique identifier for each student
- Age → Age of the student
- Gender → Male or Female
- StudyHoursPerWeek → Number of hours studied per week
- AttendanceRate → Percentage of classes attended
- PreviousScore → Score obtained in previous examination
- ParentalEducation → Education level of parents (HighSchool / Graduate / Postgraduate)
- InternetAccess → Whether the student has internet access (Yes / No)
- ExtracurricularActivities → Participation in extracurricular activities (Yes / No)
- FinalScore → Final examination score of the student
- Pass → Target variable (1 = Pass, 0 = Fail)

---

⚙️ Workflow of the Project

1. Importing required Python libraries
2. Loading and exploring the dataset
3. Performing missing value analysis
4. Encoding categorical features using Label Encoding
5. Conducting correlation analysis
6. Selecting input features and target variable
7. Splitting dataset into training and testing sets (80/20)
8. Scaling features using StandardScaler
9. Training Logistic Regression model
10. Training Random Forest Classifier model
11. Predicting student outcomes
12. Evaluating model performance using metrics
13. Visualizing results using graphs
14. Comparing both model performances

---

🤖 Machine Learning Algorithms Used

**1. Logistic Regression**

Logistic Regression is a supervised Machine Learning algorithm used for binary classification problems. It predicts the probability of a student passing or failing based on the input features.

**2. Random Forest Classifier**

Random Forest is an ensemble learning method that builds multiple decision trees and merges them together to get a more accurate and stable prediction. It also provides feature importance scores.

---

📊 Data Visualization

The project includes graphical visualizations such as:

- Bar chart for Pass/Fail distribution
- Scatter plot of Study Hours vs Final Score
- Scatter plot of Attendance Rate vs Final Score
- Correlation Heatmap of all features
- Bar chart of Parental Education vs Pass Rate
- Confusion Matrix for Logistic Regression
- Confusion Matrix for Random Forest
- Feature Importance chart from Random Forest
- Model Accuracy Comparison bar chart

These visualizations help understand dataset behavior, feature relationships, and model performance.

---

📈 Model Evaluation Metrics

The model performance is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

These metrics help measure prediction accuracy and model efficiency for both classifiers.

---

🚀 Results

The trained Machine Learning models successfully predict student pass/fail outcomes based on academic and demographic features. Random Forest Classifier achieved higher accuracy compared to Logistic Regression. The most influential features were Study Hours Per Week, Previous Score, and Attendance Rate.

---

✅ Conclusion

This project demonstrates the practical implementation of Machine Learning techniques for predictive analysis in the education domain. The models effectively process student-related features, perform binary classification, evaluate performance, and visualize analytical insights through graphs and metrics.

The project successfully integrates:

- Data preprocessing
- Feature engineering
- Label encoding and feature scaling
- Model training (Logistic Regression & Random Forest)
- Prediction analysis
- Evaluation metrics
- Data visualization
- Model comparison

---

📁 Project Files

- `CodTech_Task2_Predictive_Analysis_ML.ipynb`
- `student_performance.csv`
- `README.md`
