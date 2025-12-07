**Project Description**
This project aims to build an automated predictive model that determines whether a loan application will be approved or rejected. Traditional loan approval relies heavily on human judgment, which can introduce bias, inconsistency, and delays—especially when processing large volumes of applications. To overcome these limitations, the project utilizes machine learning to analyze demographic, credit-related, financial, and behavioral factors, enabling a more objective and data-driven approval process.
The model is designed to handle missing or incomplete data and adapt to changing financial conditions. By learning from past applicant profiles and outcomes, the system provides reliable predictions that support faster and fairer loan decisions.

 **Project Objective****
•	To develop a machine learning model that accurately predicts loan approval or rejection.
•	To reduce s**ubjectivity and human bias in the loan evaluation process.
•	To incorporate applicant demographic, financial, credit history, and socio-economic variables in decision-making.
•	To ensure the model can handle missing or incomplete information.
•	To build a scalable system that adapts to dynamic financial conditions and updated applicant data.
•	To support financial institutions in achieving faster, consistent, and risk-aware loan assessments.

**Process Involved****
1.	Problem Understanding
Identified the need for an automated, objective, and scalable loan approval prediction system.

2.	Data Loading & Preprocessing
 - Cleaned column names and formatted strings.
 - Handled categorical values through mapping (Graduate/Not Graduate, Yes/No, Approved/Rejected).
 - Verified dataset completeness and prepared numerical features.
   
3.	Exploratory Data Analysis (EDA)
- Visualized distribution of approvals.
- Analyzed relationships between CIBIL score, income, loan amount, and assets.
- Identified key drivers such as credit score and income level.
   
4.	Feature Selection -
- Selected important demographic, financial, and credit-related fields for model training.
   
5.	Model Development
- Used Logistic Regression.
- Split data into training and testing sets (80/20 with stratification).
- 
6.	Model Evaluation
- Calculated Accuracy, Precision, Recall, F1-score, ROC-AUC.
- Generated confusion matrix to understand false approvals and rejections.

7. Prediction & Interpretation
- Model outputs probability of approval for new applicants.
- Interpreted key trends influencing approvals.
________________________________________
**Summary**
* The study successfully developed a logistic regression model capable of predicting loan approval with strong performance (Accuracy 80%, ROC-AUC 0.88). 
* The model identifies CIBIL score, income, loan amount, and asset values as major contributors to approval outcomes. 
* It effectively reduces human bias, handles large-scale data, and supports consistent decision-making. 
* The system is also flexible enough to work with incomplete information and adapt to changes in applicant financial status. 
* Overall, this automated model enhances accuracy, efficiency, and fairness in loan approval processes.
