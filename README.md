# PRODIGY_DS_03
# 🌳 Task-03: Decision Tree Classifier – Prodigy InfoTech Internship

📌 Objective
This project is part of the Prodigy InfoTech Data Science Internship. The goal of this task is to build a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The model helps in understanding decision-making patterns and predicting customer behavior using classification techniques.

📂 Task Description
> Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.

🗂️ Dataset Used
Dataset Source: [Prodigy InfoTech](https://github.com/Prodigy-InfoTech) - Task 3 Dataset
Dataset: Bank Marketing Dataset
Features: Age, job, marital status, education, balance, contact type, previous outcomes, etc.
Target: Whether the customer subscribed to a term deposit (Yes/No)

🤖 Model Building
Preprocessing:
Handled categorical features using label encoding and one-hot encoding
Managed missing values and cleaned the data

Model:
Built using DecisionTreeClassifier from scikit-learn
Trained and tested the model on labeled data

Evaluation:
Accuracy score, confusion matrix, classification report
Visualized the decision tree structure

📈 Tools & Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

✅ Results & Conclusion
The decision tree classifier successfully predicted customer purchasing behavior with a good accuracy score. The model also provided clear interpretability, showing which features most influenced the prediction. This approach can help businesses in targeting potential customers more effectively.
