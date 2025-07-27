Student Performance Prediction using Machine Learning

This project applies supervised machine learning techniques to predict university student performance levels (Excellent, Good, Average, Poor) early in the semester, helping educational institutions proactively support at-risk students and optimize academic resources.

📌 Problem Statement
Universities often struggle to identify struggling students early enough for effective intervention. Manual monitoring and generic academic policies are inefficient. This project builds a scalable classification model to flag at-risk students based on academic history, engagement metrics, and socio-demographic data.

💡 Objectives
Predict student performance early using machine learning.

Identify key factors influencing academic outcomes.

Enable timely academic interventions to improve retention and success rates.

Ensure privacy and fairness in predictions.

🧠 Machine Learning Techniques
Two main algorithms were implemented:

Decision Trees (Final model – 98.98% test accuracy)

Support Vector Machines (SVM) (Best SVM – 77.16% test accuracy)

🧪 Dataset
Collected from internal university systems

Features include:

Academic: Previous GPA, current GPA, attendance, study hours

Engagement: Co-curricular activity, skills development, social media use

Demographics: Gender, birth country, household income, disabilities

Target: Student performance category (Excellent/Good/Average/Poor)

All personally identifiable information (PII) was removed to ensure compliance with data privacy standards.

🛠️ Data Preparation
Removed irrelevant and sensitive fields

Addressed missing values and outliers

Feature engineering (e.g., GPA improvement)

One-hot encoding of categorical variables

Standardized numeric features

Train-test split with stratification

⚙️ Modeling & Tuning
Trained multiple Decision Tree and SVM models

Tuned hyperparameters such as max_depth, min_samples_split, C, gamma, and kernel types

Evaluated using accuracy, precision, recall, F1-score, and confusion matrix

Final Decision Tree model (depth=8) offered excellent balance between interpretability and accuracy

✅ Key Outcomes
98.98% test accuracy with Decision Tree

High precision and recall in identifying ‘Poor’ performers

Significant potential to improve retention and optimize student support allocation

Framework for ethical deployment with fairness checks and privacy safeguards

🔒 Ethics & Privacy
Anonymized data

Ensured fair treatment across gender, socioeconomic status, and Indigenous status

Included considerations for model interpretability and non-discrimination

📈 Future Work
Expand to larger or real-time datasets

Implement ensemble methods (e.g., Random Forest, XGBoost)

Automate intervention recommendations based on risk scores

Explore fairness-aware ML models
