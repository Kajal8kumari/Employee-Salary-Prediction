# Employee-Salary-Prediction
This project classifies whether a person earns more than $50K per year using demographic data. Various machine learning models are trained and evaluated to find the best-performing one.

📌 Problem Statement
To predict whether an individual's annual income is greater than $50K based on attributes such as age, education, occupation, and more using the Adult Census Income Dataset.

📂 Dataset
Source: UCI Machine Learning Repository
Dataset Name: Adult Census Income
Target: Income (<=50K or >50K)

⚙️ Requirements
Python 3.8+
Libraries: numpy, pandas, scikit-learn, joblib
Install them with:
pip install numpy pandas scikit-learn joblib

🧠 Approach
Data Preprocessing (handle nulls, label encode categorical data)
Train and evaluate ML models:
Logistic Regression
Random Forest
KNN
SVM
Gradient Boosting

Compare accuracy and select the best model
Save the best model as best_model.pkl

🚀 How to Run
Run model_training.py to train and save the model
Run predict.py to input features and get prediction (>50K or <=50K)

✅ Output
Best model achieved ~88% accuracy (varies by random split)

🔮 Future Scope
Web deployment (Flask/Django)
Add GUI
Hyperparameter tuning
Use deep learning

📚 References
UCI Adult Dataset
Scikit-learn Documentation
IBM SkillsBuild Internship Resources

👩‍💻 Developed by
Kajal Kumari
B.Tech 3rd Year, Software Engineering
C.V. Raman Global University
