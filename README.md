# Hospital-Readmission-Analysis-And-Prediction
Aimed at identifying key factors leading to patient readmissions and building a predictive model using Python. Includes data cleaning, EDA, and machine learning (XGBoost) to help hospitals reduce readmission rates and improve overall patient care efficiency.




Hospital Readmission Analysis & Prediction


Project Overview

Unplanned hospital readmissions are a major challenge for healthcare systems, driving up costs and reducing patient satisfaction. This project analyses 101,766 patient encounters with 50 features (demographic, clinical, and medication-related variables) to identify risk factors and predict readmission likelihood.



Objectives

•	Identify patterns and drivers of hospital readmissions
•	Explore patient demographics, diagnoses, and discharge dispositions influencing outcomes
•	Develop predictive models to flag high-risk patients
•	Provide actionable insights for healthcare providers to reduce readmission rates



Exploratory Data Analysis (EDA)

Key findings from the dataset:

•	Readmission Rate: 46.1% of patients were readmitted; 11.2% within 30 days
•	Age Impact: Lowest readmission in children (1.8%), highest in young adults (14.3%), and consistently high (11–12%) in patients above 60
•	Admission Source: Emergency room admissions had the highest readmission rate (~15.5%)
•	Diabetes Management: Patients with “up” or “down” changes in insulin usage showed higher readmissions (13–14%) vs steady usage (~10%)
•	Number of Diagnoses: Readmission risk increased sharply with multiple comorbidities (~27% at 11 diagnoses)
•	Discharge Disposition: Patients sent to skilled nursing facilities or home with healthcare support had higher readmissions (16–14.7%) compared to normal home discharge (~9.3%)



Predictive Modeling

•	Applied Logistic Regression using time_in_hospital and other features
•	Achieved ~88% accuracy, but with limitations (high accuracy from class imbalance, low recall for positive readmissions)
•	ROC-AUC score: 0.55 (room for model improvement with more features/advanced ML techniques)


Key Insights

•	High-risk groups: Young adults (20s), elderly (60+), patients with multiple diagnoses, unstable diabetes treatment, and those discharged to special care
•	Actionable Recommendations:
•	Enhance discharge planning & follow-ups for emergency admissions
•	Closely monitor diabetes patients with fluctuating insulin usage
•	Provide targeted post-discharge support for patients with multiple chronic conditions



Tools & Technologies

•	Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

•	Jupyter Notebook

•	Dataset: Hospital Readmission (UCI Repository / Provided CSV)

